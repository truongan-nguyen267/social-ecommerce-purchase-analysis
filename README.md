# Social E-commerce Purchase Analysis

## Problem

Understanding what drives purchase behavior in social e-commerce is critical for improving conversion.

However, not all strong signals are true drivers. Some behaviors occur late in the user journey and simply indicate purchase intent rather than cause it.

This project investigates what drives purchase behavior and separates true drivers from late-stage conversion signals.

## Approach

- Performed exploratory data analysis (EDA) to examine relationships between user behavior and purchase outcomes
- Compared feature impact across different stages of the user journey
- Built interpretable models to validate patterns and identify key influencing factors
- Used SHAP analysis to understand feature importance and direction

## Key Insights

- High user familiarity (user level) is strongly associated with higher conversion
- Following a creator increases trust and likelihood of purchase
- Discount shows a threshold effect rather than a linear relationship
- Shorter interaction gaps (last_click_gap) correlate with higher conversion
- Late-stage behaviors such as add-to-cart and coupon usage are strong predictors, but represent conversion signals rather than true drivers

## Business Impact

- Focus on improving early-stage engagement rather than only optimizing final conversion steps
- Build trust through creator interactions and platform familiarity
- Use discounts strategically instead of applying them uniformly
- Reduce friction earlier in the user journey to improve overall conversion
