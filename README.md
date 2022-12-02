## Shack-Labs-Data-Scientist-Assignment
Completed the following 2 tasks as part of Shack Labs Data Scientist Assignment:

1.House Price Prediction

2.Matching of Amazon and Flipkart Products
## Libraries & Frameworks Used
**For Task 1: House Price Prediction**

Numpy, Pandas, Matplotlib, Seaborn, Scikit-learn, Scipy, XGBoost, LightGBM, CatBoost

**For Task 2: Product Matching**

PyTorch, Sentence Transformers, Pandas

## Machine Learning Models Performance Comparison for Task 1: House Price Prediction
**Drawbacks related to Underlying Assumptions of Machine Learning Algorithms**

The assumptions associated with regression modeling and machine learning in general are as follows:

Multicollinearity : There is minimal or no multicollinearity among the independent variables. It usually requires a large sample size to predict properly. It assumes the observations to be independent of each other. 

Homoscedasticity: The variance of residual should be the same for any value of X.

Observations are assumed to be independent of each other.

For most of the machine learning algorithms such as Linear Regression and many clustering algorithms, normal distribution is necessary for producing better outcomes.

Unstability: Tree-based models are relatively unstable. A small change in the data can cause a large change in the structure of the decision tree causing instability.

Non-scalability: Several boosting models such as XGBoost and Gradient Boosting models are very sensitive to outliers since every classifier is forced to fix the errors in the predecessor learners. The overall method is hardly scalable. Moreover, they don't perform well enough on sparse and unstructured data due to their internal working and underlying assumptions.
|  Model | R2 Score (%)|
| ----| ---|
|Cat Boost Regressor|	81.39|
|Extra Trees Regressor|	78.51|
|Gradient Boosting Regressor|	77.02|
|Hist Gradient Boosting Regressor|	75.85|
|Random Forest Regressor|	75.26|
|LGBM Regressor|	74.72|
|Bagging Regressor|	74.19|
|XGBRegressor|	71.04|
|MLP Regressor |	64.52|
|LinearRegression|	64.38|
|SVR|	59.28|
|KNeighborsRegressor|	54.22|
|Decision Tree Regressor|	50.12|
