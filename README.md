# consumer_damage_analysis

소비자 피해 위험도 분석 및 예측 모델 구축
프로젝트 개요

소비자원 피해구제 데이터를 활용하여 소비자 피해 발생 패턴을 분석하고, 특정 거래 유형에서 발생할 수 있는 위험도를 예측하는 프로젝트입니다.

본 프로젝트는 단순 통계 분석에 그치지 않고,

위험 유형 탐색
통계적 검정
로지스틱 회귀 분석
랜덤포레스트 모델링
위험 점수화(Risk Scoring)
Tableau 대시보드 구축

까지 수행하였습니다.

# 프로젝트 목표
소비자 피해 발생 구조 파악
판매채널, 계약유형, 품목군별 위험 특성 분석
피해 발생 가능성이 높은 거래 유형 식별
위험도 점수화 모델 개발
시각화를 통한 정책·실무 활용 가능성 제시
# 사용 기술
Data Analysis
Python
Pandas
NumPy
Scikit-learn
Database
MySQL
Visualization
Tableau
Statistical Analysis
Chi-Square Test
Standardized Residual Analysis
Logistic Regression (Odds Ratio)
# 데이터 구성
주요 변수
변수	설명
age_group	연령대
sales_channel	판매채널
contract_mode	계약유형
item_group	품목군
risk_type	위험유형
regime	코로나 전·후 구분

# 분석 프로세스
Raw Data
    ↓
Data Preprocessing
    ↓
Exploratory Data Analysis
    ↓
Statistical Testing
    ↓
Logistic Regression
    ↓
Machine Learning Modeling
    ↓
Risk Scoring
    ↓
Tableau Dashboard


# 주요 분석 내용
## 1. 통계 검정
카이제곱 검정 수행
판매채널 × 위험유형
계약유형 × 위험유형
품목군 × 위험유형

## 2. 표준화 잔차 분석

위험 발생에 영향을 크게 미치는

판매채널
계약유형
품목군

식별

## 3. 로지스틱 회귀 분석

Odds Ratio(OR)를 활용하여

고위험 판매채널
고위험 계약유형

도출

# 4. 머신러닝 모델링

구축 모델

Logistic Regression
Random Forest

목표

위험 발생 가능성 예측
주요 영향 변수 도출
# 5. 위험도 점수화 모델

각 변수별 가중치를 활용하여

판매채널 위험도
+
계약유형 위험도
+
품목군 위험도
=
최종 위험 점수

를 산출하는 Risk Score 모델 개발

Tableau Dashboard

## 주요 기능

연령대별 위험 현황
판매채널별 위험 분석
품목군별 위험도 비교
연도별 변화 추이
위험도 TOP 거래 유형 탐색
