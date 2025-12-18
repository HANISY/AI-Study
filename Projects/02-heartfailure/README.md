## 프로젝트 배경
- 임상적 필요성: 심부전은 높은 사망률을 보이는 질환으로, 환자의 예후를 조기에 예측하여 고위험군을 선별하는 것이 필수적임.

- 데이터 기반 의사결정: 직관적인 판단이 아닌, 임상 기록 데이터를 기반으로 객관적인 생존 확률을 예측.

- 기대 효과: 주요 사망 위험 요인을 식별하여 의료진이 환자 모니터링 우선순위를 수립하는 데 기여하고자 함.
## 데이터셋 소개

|변수명|설명|
|:---:|---|
|age|환자의 나이|
|anaemia|빈혈 여부 (0: 정상, 1: 빈혈)|
|creatinine_phosphokinase|크레아틴키나제 수치(근육 기능 지표)|
|diabetes|당뇨 여부 (0: 정상, 1: 당뇨)|
|ejaction_fraction|박출계수(심장이 수축할 때 나가는 혈액의 비율) (%)|
|high_blood_pressure|고혈압 여부 (0: 정상, 1: 고혈압)|
|platelets|혈소판 수 (kiloplatelets/mL)|
|serum_creatinine|혈중 크레아티닌 수치(신장 기능 지표) (mg/dL)|   
|serum_sodium|혈중 나트륨 수치 (mEq/L)|
|sex|성별 (0: 여성, 1: 남성)|
|smoking|흡연 여부 (0: 비흡연, 1: 흡연)|                   
|time|관찰 기간 (일)|     
|DEATH_EVENT|사망 여부 (0: 생존, 1: 사망)|

## 목표

제한된 임상 데이터 환경(n=299)에서의 과대적합 문제를 해결하고, 심부전 환자의 생존율 예측을 위한 최적의 일반화 모델 구축을 목표로 합니다. 

## 결과

<img src="https://github.com/HANISY/AI-Study/blob/main/Projects/02-heartfailure/img/HeartFailure_result.jpg?raw=true">

💻 [전체 코드 확인](https://github.com/HANISY/AI-Study/blob/main/Projects/02-heartfailure/heartfailure.ipynb)
