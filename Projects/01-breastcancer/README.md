## 프로젝트 배경
유방암은 세계에서 가장 흔한 여성암입니다. 여성암의 약 24%를 차지하며, 사망률 또한 15.5%로 가장 높다.

2기 이내 유방암 환자의 5년 생존율은 91.8%를 넘을 정도로, 일찍 발견되면 완치 가능성이 높다. 

따라서 유방암은 조기 발견이 무엇보다 중요하다고 할 수 있다. 

(출처: 강남세브란스병원)

## 데이터셋 소개

1995년 Dr. William H. Wolberg가 주도하여 수집된 위스콘신 대학교 병원에서 얻은 유방 종괴의 미세 바늘 흡인물 이미지를 기반으로 한 데이터

|기본 특성|설명|
|------|------|
|Radius (반경)|핵 경계선의 평균 거리|
|Texture (질감)|회색조 이미지에서 핵 표면의 표준 편차 (명암 대비)|
|Perimeter (둘레)|핵 경계선의 총 길이|
|Area (면적)|핵의 크기|
|Smoothness (평활도)|핵 경계선의 지역적 변화 (울퉁불퉁함 정도)|
|Compactness (조밀도)|P2/A−1.0 (둘레 제곱 / 면적 - 1.0)으로 계산된 정도|
|Concavity (오목함)|핵 경계선의 오목한 부분의 심각도|
|Concave Points (오목점)|핵 경계선의 오목한 부분의 수|
|Symmetry (대칭)|핵의 모양이 얼마나 대칭적인지|
|Fractal Dimension (프랙탈 차원)|핵 경계선이 얼마나 복잡한지|

1. Mean (평균): 해당 특성의 평균값
2. Standard Error (표준 오차): 해당 특성의 변동성을 나타내는 표준 오차
3. Worst (최대/최악): 해당 특성의 가장 큰(최악의) 값. 이는 종양의 가장 공격적인 특징을 반영

&nbsp;

## 목표

머신러닝 모델링을 통한 유방암 진단 정확도 확보 및 악성 판별의 핵심 인자를 규명할 수 있다. 

<img src="https://github.com/HANISY/AI-Study/blob/main/Projects/01-breastcancer/breastcancer_result.png?raw=true">

💻 [전체 코드 확인](https://github.com/HANISY/AI-Study/blob/main/Projects/01-breastcancer/breastcancer.ipynb)
