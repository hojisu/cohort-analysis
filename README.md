# cohort-analysis

Reward Marketing을 통해 매출 증대가 발생했는지 이중차분법 인과추론을 통한 코호트 분석

## 목적
  - Reward Marketing으로 매출에 유의미한 증대가 발생했는지 여부 확인

## 데이터
  - 포인트 지급 로그
  - 사용자의 주문 정보

## 이중차분법(Difference-in-Differences Estimation)
### [Cohort Analysis](https://github.com/hojisu/cohort-analysis/blob/master/cohort_analysis.ipynb)
  - 개입을 받는 그룹(실험군)과 그렇지 않은 그룹(대조군)의 개입 전후 결과의 차이와 실험군과 대조군의 차이 두개의 차이로 효과를 추정하는 방법
  - 포인트 지급 받기 전의 두 그룹의 매출 트렌드가 비슷하였고 포인트 지급 기간에 다른 변화는 없다고 가정
  - 이중차분법을 직접 계산하는 방법과 회귀 두가지 방법을 사용
