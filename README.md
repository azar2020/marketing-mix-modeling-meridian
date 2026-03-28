# marketing-mix-modeling-meridian
End-to-end Marketing Mix Modeling project using Google Meridian to quantify channel impact, evaluate ROI, and support budget allocation decisions.


# Marketing Mix Modeling with Google Meridian

## Overview
This project demonstrates a Bayesian Marketing Mix Model (MMM) using Google Meridian to estimate the contribution of different marketing channels to revenue.

## Objective
To quantify the impact of marketing channels and support budget allocation decisions using a privacy-safe, aggregated modeling approach.

## Dataset
Synthetic weekly data including:
- Search spend
- YouTube spend
- Revenue

## Methodology
- Bayesian MMM using Google Meridian
- Adstock and saturation effects (handled internally)
- MCMC sampling for parameter estimation
- Model diagnostics using convergence checks (R-hat, posterior predictive checks)

## Key Results
- Model successfully converged (R-hat < 1.2)
- R² ≈ 0.64
- MAPE ≈ 2.4%
- Bayesian posterior checks passed
## Visual Results

### Model Fit
<img width="826" height="404" alt="model_fit png" src="https://github.com/user-attachments/assets/b5022285-0f96-4299-bb05-cac1890a172f" />


### Channel Contribution
<img width="723" height="418" alt="image" src="https://github.com/user-attachments/assets/88b3aa34-d396-46d0-a0be-5fbc0247ca94" />


## Insights
- Estimated channel contributions to revenue
- ROI signals identified per channel
- Model suitable for budget optimization

## Tools
- Python
- Google Meridian
- TensorFlow Probability
- Pandas / Matplotlib

## Next Steps
- Add budget optimization scenarios
- Extend to multi-channel model
- Incorporate incrementality validation

