# Nasdaq Closing Cross Predictive Analytics-Regression Problem

The project aims to predict the closing price movements of numerous NASDAQ-listed stocks, using the Nasdaq Closing Cross auction data in the last 10 minutes. The metric used to evaluate five models’ performance is RMSE since RMSE is highly sensitive to large errors, which is crucial in this regression problem where large prediction errors can have significant consequences.In this time-series problem, uncertainties from splitting and non-deterministic models were addressed by performing Expanding window method. Models are fitted using GridSearchCV and their performance are assessed by calculating RMSE on the test set for each window.Finally, the best model along with its validation and test scores are recorded in a list.

Required library versions:
python=3.11.5
matplotlib=3.7.2
pandas=2.0.3
scikit-learn=1.1.1
numpy=1.24.0
xgboost=2.0.2
shap=0.43.0
jupyter_client=7.3.1
jupyter_core=4.10.0
jupyterlab=3.6.3
jupyter_server=1.17.0
jupytext=1.13.8
rise=5.7.1
plotly=5.9.0
ipywidgets=8.0.4

