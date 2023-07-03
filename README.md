<div align="center">
<h1> 🫀 Heart disease classification</h1> 
figure out if you have heart disease or not
</div>

## 💠 Introduction
This notebook explores the utilization of diverse Python-based machine learning and data science libraries to develop a predictive machine learning model with the objective of determining whether an individual has heart disease or not, based on their following medical attributes. 

Some features are (in total 14):
- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholestoral in mg/dl
- etc.

Target variable will be:
- 0 : No heart disease
- 1 : Heart disease

## 💠 Tested models
Our analysis included six distinct machine learning models ( mainly from scikit-learn ): `LogisticRegression()`, `KNeighborsClassifier()`, `RandomForestClassifier()`, `XGBClassifier()`, `GaussianNB`, and `CatBoostClassifier()`. And the best performance model, Logistic Regression has been chosen to be tuned with `RandomizedSearchCV()`.

## 💠 Data
[The original data](https://archive.ics.uci.edu/dataset/45/heart+disease) came from the Cleavland data from the UCI Machine Learning Repository.
