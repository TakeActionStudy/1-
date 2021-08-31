# 1주차 과제
##1. 다음의 과정까지는 기본으로 진행해주세요
```
import numpy as np
import pandas as pd
from sklearn.datasets import load_iris
df = load_iris()
flower_data = df['data']
flower_target = df['target']
```
##2. 이번 과제에서 사용할 데이터는 붓꽃 데이터입니다. flower_data의 모양은 다음과 같습니다.
![folwer_data](https://user-images.githubusercontent.com/50089365/131536107-1a4ab39e-0476-4cf0-8ea2-3159601c141a.PNG)

##3. flower_target의 모습입니다. 0은 setosa, 1은 versicolor, 2는 virginica를 가르킵니다.
![flower_target](https://user-images.githubusercontent.com/50089365/131536223-88079225-828e-4de0-a032-817ed909b4c5.PNG)

##4. 배열 인덱싱을 활용하여 모델의 정확도가 100%가 나오도록 해주세요!
###(평가 데이터는 37개로, random seed는 13으로 맞추겠습니다.)
