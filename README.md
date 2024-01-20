## Dacon 대구 교통사고 피해 예측 AI 경진대회

- 대회 개요 https://dacon.io/competitions/official/236193/overview/description
- 2023 12월 대구 교통사고 피해 예측 AI 경진대회 (0.6%이내 - 5등/942팀)
- 팀 코드 공유 https://dacon.io/codeshare/9505 
- 발표자료 [pdf](https://github.com/piabona/DG-traffic-accident-prediction/blob/e741e3a3d88d430936bdae88fbcf18f2588a7c62/docs/%E1%84%83%E1%85%A2%E1%84%80%E1%85%AE%20%E1%84%80%E1%85%AD%E1%84%90%E1%85%A9%E1%86%BC%E1%84%89%E1%85%A1%E1%84%80%E1%85%A9%20%E1%84%91%E1%85%B5%E1%84%92%E1%85%A2%20%E1%84%8B%E1%85%A8%E1%84%8E%E1%85%B3%E1%86%A8%20AI%20%E1%84%80%E1%85%A7%E1%86%BC%E1%84%8C%E1%85%B5%E1%86%AB%E1%84%83%E1%85%A2%E1%84%92%E1%85%AC_%E1%84%89%E1%85%A1%E1%86%B7%E1%84%8E%E1%85%A9%E1%86%BC%E1%84%89%E1%85%A1.pdf)

## Summary
- Data selection (Daegu + 6 metropolitan cities)
- Label encoding, Target encoding / Standard scaling
- Catboost, LightGBM, NGBoost model with Optuna
- 10Fold, 3 Seed ensemble

## Data Preprocessing 
- Target encoding, Label encoding 
- Standard Scaling 

## Model 
- ML CatBoost, LightGBM, NGBoost
- Optuna hyperparameter tuning

## Ensemble 
- 10Fold, SEED ensemble

## Environment
- OS : Linux-6.1.58+-x86_64-with-glibc2.35
- Google Colab GPU
  ```
  sys : 3.10.12 (main, Nov 20 2023, 15:14:05) [GCC 11.4.0]
  python : 3.10.12 (main, Nov 20 2023, 15:14:05) [GCC 11.4.0]
  pandas : 1.5.3
  numpy : 1.23.5
  sklearn : 1.2.2
  lgbm : 4.1.0
  catboost : 1.2.2
  ngboost : 0.4.2
  ```
