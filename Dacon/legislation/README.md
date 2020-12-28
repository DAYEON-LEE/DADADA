# 국회 입법활동 빅데이터 시각화 경진대회 
### 기간 : 2020.11.24~2020.12.28 

## 주제 - 11가지 궁금증을 해결하며 알아가는 입법 시각화 


※ 사용한 라이브러리 
```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import os
import re
import datetime as dt
import warnings 
warnings.filterwarnings(action='ignore')
from PIL import Image
```

### 1. 대수별 국회의원 수의 변화 
### 2. 대수별 국회의원 출생지 
### 3. 대수별 발의법의안 건수 
### 4. 5년간 월별 발의법의안 건수 
### 5. 대수별 발의법의안 처리상태 
### 6. 발의법의안을 가장 많이 제시한 국회의원 
### 7. 최근 5개 대수별 어떤 종류의 법률안이 안건되는지
### 8. 대수별 본회의 처리안 건수는 어떻게 달라지는지
### 9. 대수별 총득표수 찬성,반대, 기권 비율은 어떤지
### 10. 대수별 안건을 제안하고 공포까지 걸리는 시간
### 11. 제안일과 공포일의 월별, 요일별 분포

이렇게 총 11가지의 질문을 제시하며 분석을 진행하였습니다. 

데이콘 주소 : https://dacon.io/competitions/official/235679/codeshare/2019
