# Oil-Well-Optimization
Oil Well Location Optimization using Machine Learning

## Project Overview
This project focuses on selecting the most profitable region to develop 200 oil wells using predictive modeling and risk analysis.

## Objectives
- Predict oil reserves using machine learning
- Select top-performing wells
- Maximize profit while minimizing risk
- Identify the best region for investment

## Tools & Technologies
- Python (pandas, NumPy, scikit-learn)
- Jupyter Notebook

## Methodology
- Data preprocessing and validation
- Train-test split (75/25)
- Linear Regression modeling
- RMSE evaluation
- Profit calculation based on business constraints
- Bootstrapping (1000 samples) for risk analysis

## Key Metrics
- Budget: $100M
- Wells selected: 200
- Revenue per unit: $4500

## Key Findings
- Average reserves below profitability threshold → selection is critical
- Region 0 showed high profit but unacceptable risk (6%)
- Region 1 achieved:
  - Highest average profit
  - Risk < 2.5%
  - Stable confidence intervals

## Business Impact
- Data-driven decision-making reduces financial risk
- Bootstrapping provides reliable uncertainty estimation
- Optimal selection strategy is more important than average performance

## Conclusion
Region 1 is the best choice due to its balance between profitability and low risk.

## Next Steps
- Test more advanced models (Random Forest, Gradient Boosting)
- Incorporate more features for better predictions
- Real-time decision systems
