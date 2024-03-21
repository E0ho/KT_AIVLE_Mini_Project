# 2차 미니프로젝트
![장애인 콜택시](https://www.sisul.or.kr/open_content/calltaxi/images/visual_img.jpg)


# 주제
> 장애인 이동권 개선을 위한 장애인 콜택시 대기시간 예측 머신러닝 모델 개발

<br>

## 개발 배경
- 교통약자 이동권을 개선하기 위해 도입된 장애인 콜택시 사업의 불규칙한 차량 대기시간으로 인해 이용자와 제공자 모두가 어려움을 겪고 있다.

- 이에, 과거 2015년 ~ 2022년 장애인 콜택시 운행 정보와 날씨 정보 등을 활용하여, 차량 호출 전 차량 대기 시간을 예측하는 모델을 개발하고자 한다.


<br><br>

## 기대 효과
- 고객 : 차량 호출 전, 차량 대기시간을 미리 확인할 수 있다. <br>
- 정부 : 차량 대기시간이 길 것으로 추측되는 날, 운행 차량을 늘릴 수 있다.

<br><br>

## 데이터 분석 방법
- 운행 정보에 따른 차량 대기시간 (접수건, 탑승건, 운행 차량 수)

- 날씨에 따른 차량 대기시간 (강수, 폭염)

- 평일, 주말에 따른 차량 대기시간

- 공휴일로 인한 오차 고려 

- 2020 ~ 2022년 코로나로 인한 오차 고려 

<br><br>

## Regression 모델
- Linear Regression
- KNN Regressor
- Decision Tree Regressor
- Random Forest Regressor
- XGBR Regressor
- LGMB Regressor


<br><br>

### Notion 링크
> https://www.notion.so/6c4e0f3adf464aaaac25053425561a2e?pvs=4
