# 전기차 가격 예측 해커톤: 데이터로 EV를 읽다!

![car-6943487_1280](https://github.com/user-attachments/assets/cb54f8ea-73c4-4881-ae4e-1e9c4e8737ea)

## 배경

전기차 가격 예측은 빠르게 성장하는 전기차 시장에서 소비자와 제조사 모두에게 중요한 가치를 제공합니다.

정확한 가격 예측은 시장 경쟁력 분석, 소비자 구매 의사 결정 지원, 그리고 생산 및 유통 최적화에 기여할 수 있습니다.

전기차의 다양한 데이터를 바탕으로 가격을 예측하는 AI 알고리즘을 개발하는 것을 목표


## 프로젝트 기간

2025.01.05 ~

## Process

|Stage|Activity|Date|Comment|Code Link|
|--|--|--|--|--|
|1|EDA|2025.01.04|데이터 탐색 및 시각화|[EDA](https://github.com/SeokcheonMoon/dacon_EV_analysis/blob/main/Data_analysis/EDA.ipynb)|
|2|ML|2025.01.05|머신러닝 예측 모델 개발|[ML](https://github.com/SeokcheonMoon/dacon_EV_analysis/tree/main/ML)|

## 분석결과

## 머신러닝 모델 개발

|No|Date|모델|Comment|평가 점수|Best|
|--|--|--|--|--|--|
|1|2025.01.05|XGBRregressor|배터리용량 결측값을 평균값으로 대체|1.0153660952||
|2|2025.01.14|XGBRregressor|배터리용량 결측값을 0으로 대체|0.9181333378|V|
|3|2025.01.15|LGBMRregressor|배터리용량 결측값을 0으로 대체|0.9449329324||
|4||||||

## 데이콘 등수 기록 (참여 인원 : 1,137명)

- 2025.01.05 219등
- 2025.01.14 52등

## Reference

[데이콘](https://dacon.io/competitions/official/236424/overview/description)