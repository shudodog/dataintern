# dataintern

# asthma-decisiontree

https://github.com/shudodog/asthma-decisiontree

**2021.01**

**Python, Q-Gis**

## 설명
전국 지역별로 유병률을 Moran's I 를 이용해 데이터 분석을 하여 decision tree로 나타내었다.

![image](https://user-images.githubusercontent.com/76150392/129466227-3b2103c5-2b97-48e0-966e-8c435f82e5af.png)

![image](https://user-images.githubusercontent.com/76150392/129466230-168270ec-8f8e-429a-9c82-4e36fd2655a5.png)

![image](https://user-images.githubusercontent.com/76150392/129466232-16b33a0f-fc21-4be7-b984-a38ec9a2043c.png)

## 어려웠던 점
1. decision - tree에 대한 코드 정보가 R에 비해 python이 적었다. 코딩 할때 구글링 해서 참고한 곳의 데이터와 나의 데이터가 달라서 데이터를 가공하는데 어려움이 있었다. 하지만, 구글링을 통해 내가 사용하려는 유병률 데이터와 최대한 비슷한 데이터를 쓴 코드를 참고하면서 수정하여 decision tree를 완성할 수 있었다.

# taxi-G_local

https://github.com/shudodog/taxi-G_local

**2021.01**

**Python, Q-Gis**

## 설명
서울 택시데이터를 이용하여 지역별 Hot spot, Cold Spot를 Local-G방식으로 데이터 분석하여 시각화하였다.
![image](https://user-images.githubusercontent.com/76150392/129466154-2fa15f42-31d6-43f6-b717-352ddf1b1452.png)

## 어려웠던 점
1. Local-G 방식을 이해하고 코드로 구현하는 것이 어려웠다. 영어의 중요성이 느껴졌다.
2. taxi-data의 양이 굉장히 많아 한번 데이터를 수정하는데 몇십 분씩 걸렸다. 그래서 코드를 한번 잘못 짜거나 실수 하면 데이터 가공부터 다시 해야했는데, 그 부분에서 시간이 쓸데없이 많이 소비되어 예상보다 늦게 완성하였다.

# taxidata_analysis_weekly_hourly

https://github.com/shudodog/taxidata_analysis_weekly_hourly

**2021.02**

**Python, excel**

## 설명
2019년 6,7월 택시 데이터 승/빈차수를 요일별로 Python으로 데이터를 가공하고 excel로 나타내었다.

![image](https://user-images.githubusercontent.com/76150392/129466306-1422c657-71ce-45a9-b0aa-a4423c5a811b.png)
![image](https://user-images.githubusercontent.com/76150392/129466309-95becd33-f4b8-46a4-aaa1-7fb849718675.png)
![image](https://user-images.githubusercontent.com/76150392/129466312-01b548dd-5f34-4469-b973-6841141a392a.png)
![image](https://user-images.githubusercontent.com/76150392/129466313-d4b5e36f-449d-4ce0-a90c-9400e1cd85b3.png)

# 어려웠던 점
1.taxi data 양이 많아서 컴퓨터가 데이터 분석하는데 오래걸렸다. 그래서 앞선 taxi-G-local과 마찬가지로 코드를 한번 잘못 짜거나 실수 하면 데이터 가공부터 다시 해야했는데, 그 부분에서 시간이 쓸데없이 많이 소비되어 예상보다 늦게 완성하였다.


# civil_machinelearning

https://github.com/shudodog/civil_machinelearning

**2021.02**

**Python**

## 설명
건물 균열 사진들을 라벨링하고(약3000개)
Python을 이용해 test와 train으로 나누고 머신러닝으로 데이터를 학습시키고 새로운 파일을 넣어봤을때 정확도 결과를 확인하였다.

## 배운 점
1.label을 더 디테일하게 한게 오히려 정확도가 더 떨어졌다. 인턴 3명이서 3000장의 사진을 매우 디테일하게 라벨링하였는데 정확도가 30퍼센트 대로 기존 것(60퍼센트 대) 보다 정확도가 떨어졌다. 이것은 이미지를 너무 확대해버리면 균열이 검은 색으로 표시되는데 그것이 오히려 정확도를 낮춘 것이다.
