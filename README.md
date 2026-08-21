# semiconductor_ai
반도체 공정 데이터를 머신러닝 기반으로 분석하여 주요 공정 변수와 불량 원인을 도출하고, 분석 결과를 시각화해 최종 공정 개선 보고서로 제작한 프로젝트
## 프로젝트 보고서

[Etch 공정 데이터 분석 보고서 보기](https://nhbm2877-crypto.github.io/semiconductor_ai/etch/project_01/)
## Etch 공정 데이터 분석

### 프로젝트 개요
Etch 공정의 900개 Wafer 데이터를 기반으로 공정 변수와 Etch Rate, Uniformity의 관계를 분석한 프로젝트입니다.

데이터 전처리 및 EDA를 수행한 후 머신러닝 모델을 활용해 주요 영향 인자를 분석하고, 설비별 공정능력과 Target 중심 이탈을 비교했습니다. 최종적으로 ESC Temperature, Source RF, Bias RF, Chamber Pressure를 DOE 후보 인자로 선정하여 공정 개선 방향을 제안했습니다.

### 분석 프로세스
Raw Data 검증 → 데이터 전처리 → EDA → 공정능력 분석 → 머신러닝 모델링 → 주요 변수 선정 → DOE 설계
