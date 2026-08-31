# 2025 ML 제출 코드

MNIST 기반 분류 모델 학습 및 앙상블 실험 코드 모음.

## 폴더 구성

- `base model_train (로지스틱 같은..)/` — 로지스틱 회귀(+SGD), DT, RF, GB, KNN, SVM, MLP 등 베이스 모델 학습
- `데이터클리닝/` — 데이터 클리닝 전후 비교, 데이터 확인, 병합 데이터셋 클리닝
- `split 기준 잡기 ( 보고서 2.1.2 train - valid 분배에서 썼던 )/` — train/valid 분배 기준
- `증강 코드 ( x 1 2 4 )/` — 데이터 증강 배수(x1, x2, x4)별 모델 학습(RF, GB, KNN, MLP, SVM, Ensemble)
- `learning curve/` — 모델별 learning curve 분석
- `앙상블/` — 앙상블 모델 learning curve 및 파라미터 실험
- `accuracy evaluate/` — 원본/handmade 데이터셋 검증, 전처리 파이프라인 이후 성능, 앙상블 조합 실험, 최종 모델 평가
- `SMNIST_test_25.npz` — 테스트용 데이터셋
