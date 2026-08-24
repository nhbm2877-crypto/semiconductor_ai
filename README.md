# semiconductor_ai
반도체 공정 데이터를 머신러닝 기반으로 분석하여 주요 공정 변수와 불량 원인을 도출하고, 분석 결과를 시각화해 최종 공정 개선 보고서로 제작한 프로젝트
## 프로젝트 보고서

[Etch 공정 데이터 분석 보고서 보기](https://nhbm2877-crypto.github.io/semiconductor_ai/etch/project_01/)

[Dry Etch 종료시점 예측 및 과식각 위험 판단 보고서 보기](https://nhbm2877-crypto.github.io/semiconductor_ai/etch/project_02/dry_etch_A_integrated_report.html)

[Photo 공정 데이터 분석 보고서 보기](https://nhbm2877-crypto.github.io/semiconductor_ai/photo/project_01/)


## Etch 공정 데이터 분석

### 프로젝트 개요
Etch 공정의 900개 Wafer 데이터를 기반으로 공정 변수와 Etch Rate, Uniformity의 관계를 분석한 프로젝트입니다.

데이터 전처리 및 EDA를 수행한 후 머신러닝 모델을 활용해 주요 영향 인자를 분석하고, 설비별 공정능력과 Target 중심 이탈을 비교했습니다. 최종적으로 ESC Temperature, Source RF, Bias RF, Chamber Pressure를 DOE 후보 인자로 선정하여 공정 개선 방향을 제안했습니다.

### 분석 프로세스
Raw Data 검증 → 데이터 전처리 → EDA → 공정능력 분석 → 머신러닝 모델링 → 주요 변수 선정 → DOE 설계

### 최종 보고서
[Etch 공정 데이터 분석 보고서 보기](https://nhbm2877-crypto.github.io/semiconductor_ai/etch/project_01/)


---

## Project 02 | Dry Etch 종료시점 예측 및 과식각 위험 판단

### 프로젝트 개요

Dry Etch 공정 데이터를 활용하여 Endpoint 종료시점을 예측하고 과식각 위험을 선별한 프로젝트입니다.

Train 데이터를 기반으로 예측 모델과 위험 판정 기준을 구축한 뒤 Holdout 데이터에 동결 모델을 적용했습니다. 또한 RF Source, RF Bias, Chamber Pressure, Gas Flow를 주요 인자로 선정하여 DOE를 설계하고, 모델 결과를 자동 제어가 아닌 엔지니어의 공정 의사결정을 지원하는 방향으로 활용했습니다.

### 분석 프로세스

데이터 품질 검증 → Lot 분리 학습 → Endpoint 예측 → 과식각 위험 분류 → Train·Holdout 비교 → Holdout 검증 → DOE 설계

### 최종 보고서

[Dry Etch 종료시점 예측 및 과식각 위험 판단 보고서 보기](https://nhbm2877-crypto.github.io/semiconductor_ai/etch/project_02/dry_etch_A_integrated_report.html)

[Dry Etch Endpoint·과식각 조기 경보 프로세스 보기](https://nhbm2877-crypto.github.io/semiconductor_ai/etch/project_02/dry_etch_A_pilot_alert.html)

---

## Photo 공정 데이터 분석

### 프로젝트 개요
Photo 공정 데이터를 기반으로 공정 변수와 품질 특성 간의 관계를 분석하고, 머신러닝을 활용해 주요 영향 인자를 탐색한 프로젝트입니다.

Train 데이터 기반의 모델 학습과 Holdout 데이터 검증을 분리하여 모델의 일반화 성능을 확인하고, 분석 결과를 공정 관점에서 해석했습니다.

### 분석 프로세스
Raw Data 검증 → 데이터 전처리 → EDA → Train 데이터 학습 → Holdout 검증 → 주요 변수 분석 → 공정 관점 해석

### 최종 보고서
[Photo 공정 데이터 분석 보고서 보기](https://nhbm2877-crypto.github.io/semiconductor_ai/photo/project_01/)
