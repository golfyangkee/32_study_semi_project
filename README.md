# 채용합격자의 데이터를 통한 합격 스펙 분석 및 교육과정 제시
## 기업 규모별 합격자 스펙 분석을 통한 사용자 스펙에 따른 합불 여부 파악 및 불합 시 hrd-net 교육과정 추천

### 기간: 2024.01.18 ~ 2024.02.05

### 참여 인원: 6명

### 소개
1. 기업 규모를 대기업, 중견기업, 중소기업, 공기업 으로 분류
2. 기업 규모별 합격자 스펙 크롤링
3. 머신러닝을 통한 합격자 스펙 학습 및 예측
4. 불합격 판단 시 부족한 스펙에 대한 hrd-net 교육과정 추천

### 기획의도: 희망 기업 규모에 따른 본인의 스펙의 객관적인 판단 및 부족한 점을 보충할 수 있게 하여 안정적인 합격선 도달

### 개발환경(S/W) : window 10, pycharm, jupyter notebook

### 사용한 머신러닝: logistic_regression(다항로짓), decision tree, random forest, gradient boosting tree, multinomailNB, catboost

### 사용 앙상블 모델: 배깅
- 이유1 : 데이터가 부족해 기존 데이터의 샘플링을 통해 데이터를 늘린 만큼 과적합 위험이 증가
- 이유2 : 부스팅 방식은 배깅에 비해 정확하나 과적합의 위험성이 증가하므로 배깅 방식을 이용해 앙상블을 진행

### 역할 
1. 합격자 정보 데이터 크롤링
2. 데이터 전처리 및 EDA
3. 모델 학습 및 정확도 확인
4. 모델 앙상블
