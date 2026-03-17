---
title: "Amex Default Prediction"
date: 2023-06-15
description: "Kaggle Amex Default Prediction — credit default modeling on large-scale transaction data"
tags: ["kaggle", "tabular", "finance", "gradient-boosting"]
---

## Overview

Predicting credit card default probability for American Express customers using anonymized transaction and account features. A large-scale tabular competition with heavy feature engineering requirements.

## Approach

- Extensive feature engineering over time-series transaction histories
- Gradient boosting models (LightGBM, XGBoost, CatBoost)
- Aggregation features: rolling statistics, lag features, trend indicators
- Careful handling of missing values and categorical encodings

## Links

- [GitHub Repository](https://github.com/Galliard7/amex-default-prediction)
