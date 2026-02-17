# 🏡💰 Predicting Real Estate Price Prediction 

Data Scientists, **Paolo Hilado & Alison Danvers**, were tasked with developing a machine learning model that will be used to estimate real estate based on provided explanatory variables. It is based on market historical dataset of real estate valuation collected from Sindian Dist. New Taipei City. This project is a machine learning pipeline for predicting real estate prices using various regression models. The notebook walks through data preprocessing, model selection, hyperparameter tuning, and evaluation, providing a complete end-to-end workflow.

### Key Features
- Data Preprocessing: Standard scaling of features to ensure models train efficiently.
- Modeling: Includes multiple regression algorithms:
- Linear Models: Ridge, Lasso, Elastic Net
- Tree-based Models: Random Forest Regressor, XGBoost Regressor
- Hyperparameter Tuning: Uses GridSearchCV to find the best model parameters.
- Evaluation Metrics: Focus on RMSE (Root Mean Squared Error) for cross-validation, training, and testing datasets.
- Reproducibility: Pipelines and random seeds ensure consistent results.

### Insights
- Linear Models vs Tree-based Models: Tree-based models significantly outperform linear models on this dataset, capturing nonlinear relationships and feature interactions better.
- Random Forest achieved Train RMSE ≈ 3.38, Test RMSE ≈ 7.76, and CV RMSE ≈ 7.54, showing some overfitting.
- XGBoost achieved Train RMSE ≈ 4.67, Test RMSE ≈ 6.99, and CV RMSE ≈ 7.62, demonstrating better generalization.

### Conclusion
XGBoost is preferred for this dataset because it balances accuracy and generalization better, while Random Forest slightly overfits the training data.


### Tech Stack
- Python 3.12
- scikit-learn, xgboost, numpy, pandas, matplotlib, seaborn

✔️ Check this on this [link](https://github.com/Dcroix/Predicting-Real-Estate-Price/blob/main/Real%20Estate%20Price%20Predication%20Quick%20App%20Deploy%20Version.ipynb). (right-click → Open in new tab)  
✔️ Check this on this [link](https://huggingface.co/spaces/Dcroix/HousePriceML). (right-click → Open in new tab)
