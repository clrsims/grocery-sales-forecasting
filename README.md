### Grocery‑Sales Forecasting | Corporación Favorita Kaggle (Python, CatBoost)
- Built an end‑to‑end time‑series pipeline on ≈ 125 M daily transactions (54 stores × 33 product families)—from EDA and feature engineering to automated CSV submission.
- Engineered 300 + temporal & exogenous features (lags/rolls, promo windows, oil‑price shifts, cyclic encodings, pay‑day flags, cold‑start indicators) that cut validation RMSLE from 1.24 → 0.62 vs. linear baseline.
- Trained a CatBoost regressor with native categorical handling (store‑type, product family) and log‑transformed target; ranked top 10 % of 800 teams on the public leaderboard.
- Implemented leakage‑safe splits, deterministic seeds, and null‑imputation rules, enabling fully reproducible results across GPU/CPU hardware.
- Visualized model behavior—feature‑importance bars and RMSE‑by‑iteration plots—highlighting weekend demand spikes, holiday lift, and oil‑price sensitivity for business stakeholders.
 ![image](https://github.com/user-attachments/assets/b46b1275-41e1-470a-873a-c062fd4b0511)
