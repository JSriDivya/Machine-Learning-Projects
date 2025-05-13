1. Linear regression

**Situation:** I was tasked with building a linear regression model to predict sales based on TV advertising spending.

**Task:**  The project involved building a simple linear regression model using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn, and scikit-learn.

**Action:**
1. **Data Loading and Exploration:** Loaded the advertising dataset using Pandas, examined its structure (dimensions, data types) using `shape`, `head()`, `info()`, and `describe()`.  Visualized the relationship between TV advertising spending and sales using scatter plots and pair plots from Matplotlib and Seaborn to identify a potential linear correlation.
2. **Data Preparation:** Defined independent (TV spending) and dependent (Sales) variables, reshaped them for compatibility with scikit-learn.
3. **Model Training:** Split the data into training and testing sets using `train_test_split`. Initialized a LinearRegression model, fit it to the training data using `fit()`. Determined model coefficients (slope and intercept) using `coef_` and `intercept_`.
4. **Prediction:** Made sales predictions on the test data using `predict()`.
5. **Evaluation:** Calculated the Root Mean Squared Error (RMSE) and R-squared (R2) to assess the model's performance on the test set, using `mean_squared_error` and `r2_score`.
6. **Residual Analysis and Model Validation:** Visualized residual errors to check if the linear model assumption was valid. Compared the training and test scores to assess for overfitting or underfitting.
7. **Visualization:** Created scatter plots and regression lines to visualize the data and the model's fit.

**Result:**  The linear regression model achieved an R-squared score of approximately 0.81 and an RMSE of around 2.28.  Residual analysis and comparison of training and testing scores indicated a balanced fit. The model demonstrated a good fit for the data with 81% of the variance in sales explained by TV advertising spending. The visualization confirmed a positive linear correlation and good model fit.  The model appears to be a suitable predictor of sales based on TV advertising investment.

