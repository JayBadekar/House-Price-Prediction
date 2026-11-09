California House Price Prediction :-

A machine-learning regression project that predicts median house values across 20,640 California districts using location, housing and demographic features.

Kaggle Dataset Link :- https://www.kaggle.com/datasets/camnugent/california-housing-prices


Workflow :-

Exploratory data analysis: price distribution, income vs price scatter plot, correlation heatmap
Preprocessing: mean imputation of 207 missing total_bedrooms values, one-hot encoding of ocean_proximity, 80/20 train-test split
Modelling: scikit-learn pipelines for Linear Regression, Ridge, Lasso, Decision Tree, Random Forest and XGBoost
Evaluation: MAE, RMSE and R² on the held-out test set

Results :-

Model	MAE ($)	RMSE ($)	R²
Linear Regression	50,702	70,031	0.626
Decision Tree	43,438	68,834	0.638
Random Forest	31,710	49,030	0.817
XGBoost	31,269	47,072	0.831

Key insights :-

XGBoost performed best, cutting MAE by about 38% versus the linear baseline.
Location drives price: the ocean_proximity categories account for about 57% of feature importance, and median income about 26%.

Tech stack: Python, pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn

Suggested topics/tags: machine-learning regression xgboost scikit-learn data-science house-price-prediction python california-housing
