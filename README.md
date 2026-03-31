
## tabel for the features

| # | Feature | Symmetric Disparity Coefficient | Standard Error | Z-Value |
|---|---------|----------------------------------|-----------------|---------|
| 1 | HbA1c_level | 2.5050 | 0.0032 | 776.0032 |
| 2 | blood_glucose_level | 1.3567 | 0.0032 | 419.7093 |
| 3 | age | 1.0413 | 0.0036 | 285.8344 |
| 4 | bmi | 0.5899 | 0.0034 | 173.0045 |
| 5 | smoking_history_never | 0.2738 | 0.0037 | 73.9456 |
| 6 | smoking_history_current | 0.2125 | 0.0034 | 62.0277 |
| 7 | hypertension | 0.1948 | 0.0033 | 59.1258 |
| 8 | smoking_history_former | 0.1816 | 0.0036 | 51.1319 |
| 9 | heart_disease | 0.1426 | 0.0033 | 43.4401 |
| 10 | gender_Male | 0.1343 | 0.0032 | 42.0621 |
| 11 | smoking_history_ever | 0.1333 | 0.0033 | 40.3121 |
| 12 | smoking_history_not_current | 0.1275 | 0.0034 | 37.8411 |
| 13 | gender_Other | -0.0314 | 0.0032 | -9.911 |



## project_notes 

    {
        "features": "all images for the features",
        "model_scoring": "for all model comparison data"
    }



## model_used 

    from sklearn.ensemble import RandomForestClassifier, GradientBoostingClassifier
    from sklearn.linear_model import LogisticRegression
    from xgboost.sklearn import XGBClassifier
    from sklearn.naive_bayes import GaussianNB
    from sklearn.tree import DecisionTreeClassifier
    from sklearn.neighbors import KNeighborsClassifier
    from sklearn.svm import SVC


##