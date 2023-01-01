# Citrus_fruit-_set
감귤 착과량 예측 연습
## 12/20
- Linear Regression으로 착과량 예측하기('수고' 변수 이용) -> Multiple Linear Regression으로 착과량 예측하기(모든 변수 이용)
- 232 / 275 -> 206 / 275

## 12/28
- DecisionTreeRegressor을 활용하여 착과량 예측
- 주어진 feature 모든 이용해서 예측 -> 새순 차이, 엽록소 차이 변수를 추가하여 예측
- 점수는 Multiple Linear Regression을 활용했을때 보다는 좋지 않았지만 새순 차이, 엽록소 차이 변수를 추가함으로써 예측을 좀 더 잘해주었다.

## 12/31
 - 수고, 수관폭, 새순 관련 데이터 시각화 및 정리
 - DecisionTreeRegressor을 활용하여 착과량 예측
 - Linear Regression 보다 성능이 좋지 못했다.
 
## 1/1 
 - 새순 관련 새로운 변수들 생성(새순 차이, 새순 합, 새순 평균) -> 시계열로 되어 있는 데이터를 좀 더 의미있게 변환하여 추가해주었다.
 - RandomForestRegressor을 활용하여 착과량 예측 -> GirdSearch로 최적의 파라미터를 찾고 모델 활용하여 착과량 예측
 - 54/296 -> 18/296
