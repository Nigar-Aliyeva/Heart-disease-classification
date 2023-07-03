<div align="center">
<h1> 🫀 Heart disease classification</h1> 
figure out if you have heart disease or not
</div>

## 💠 Introduction
This notebook explores the utilization of diverse Python-based machine learning and data science libraries to develop a predictive machine learning model. The objective is to determine whether an individual has heart disease or not, based on their medical attributes. 

Such as following features:
- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholestoral in mg/dl
- etc.

Target variable will be:
- 0 : No heart disease
- 1 : Heart disease

## 💠 Used models
Our analysis included six distinct machine learning models ( mainly from scikit-learn ): `LogisticRegression()`, `KNeighborsClassifier()`, `RandomForestClassifier()`, `XGBClassifier()`, `GaussianNB`, and `CatBoostClassifier()`. And the best performance model, Logistic Regression has been chosen to be tuned with `RandomizedSearchCV()`.
