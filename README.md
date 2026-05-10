# Data Analytics Portfolio

관찰 데이터의 인과 추론, ML 모델링, 회귀 분석, 통계 검정까지 — 분석 전 과정을 직접 설계하고 구현한 프로젝트 모음입니다.

---

## 프로젝트 목록

| # | 프로젝트 | 분석 유형 | 핵심 역량 | 데이터 |
|---|---|---|---|---|
| 01 | [당뇨 데이터 A/B 테스트 — 관찰 데이터에서 인과 추론까지](./01_ab-test-causal-inference/diabetes_ab_test.ipynb) | A/B 테스트, 인과 추론 | Z-test, 카이제곱, 공변량 보정(Adjusted OR), PSM | BRFSS2015 (70,692건) |
| 02 | [소상공인 조기경보 시스템 — LightGBM 앙상블](./02_ml-competition/startup_crisis_detection.ipynb) | ML 모델링 | LightGBM, 스태킹 앙상블, SHAP, 피처 엔지니어링 | 빅콘테스트 2025 (가맹점 4,244건) |
| 03 | [스트레스 지수 예측 — 변수 선택과 회귀 성능 비교](./03_regression/stress_index_regression.ipynb) | 회귀 분석 | 다중 회귀, 변수 선택, 모델 성능 비교 | 건강 설문 데이터 |
| 04 | [Mall Customers 통계 검정](./04_clustering/mall_customers_segmentation.ipynb) | 통계 검정 | t-검정, ANOVA, Tukey HSD, 카이제곱, 상관분석 | Mall Customers (200명) |

---

## 주요 역량

- **실험 설계 & 인과 추론**: 단순 비율 비교 → 공변량 보정 → PSM 흐름으로 관찰 데이터의 한계를 직접 검증
- **ML 파이프라인**: EDA 기반 피처 설계 → 모델링 → SHAP 해석 → 비즈니스 제언 연결
- **통계 검정**: t-검정·ANOVA·카이제곱·PSM까지 검정 방법 선택 근거와 해석을 함께 기술
- **분석 스토리텔링**: 각 분석에 "왜 이 방법을 선택했는가" 주석과 개념 정리 포함

---

## 기술 스택

`Python` `Pandas` `Scikit-learn` `LightGBM` `XGBoost` `Scipy` `Matplotlib` `Seaborn` `SQL`

---

## 통계 공부 노트

분석에서 막혔던 개념들을 직접 정리한 Velog 블로그: [velog.io/@myyoon2484](https://velog.io/@myyoon2484)
