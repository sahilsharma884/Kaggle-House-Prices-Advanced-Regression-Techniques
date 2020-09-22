# Kaggle-House-Prices-Advanced-Regression-Techniques
Kaggle Competition (Getting Started): House Prices: Advanced Regression Techniques (<a href='https://www.kaggle.com/c/house-prices-advanced-regression-techniques'>Competition Here</a>)

Predict sales prices and practice feature engineering, RFs, and gradient boosting

Software Used: Anaconda, Python 3.8

I have provided requirments.txt (or environment.yml)  (if needed).

Description:
```
+----------------------------------------------------------------------------------------------------------------------------------------+
| .ipynb         | Describe/Operation Performed                                                                                          |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-I:    | Read train and test csv and perform handling missing data.                                                            |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-II:   | EDA and Splitting train into train,cv,and test portion.                                                               |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-III:  | Training RandomForest Regression using all Features and hyperparameters                                               |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-IV:   | Perform Testing stage for above trained model and submitted to Kaggle.                                                |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-V:    | Perform and Training using Feature Selection with RandomForest Regression with best parameters from Notebnook-III     |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-VI:   | Perform Testing stage for above trained model and submitted to Kaggle.                                                |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-VII:  | Training GradientBoosting Regression using all Features and hyperparameters                                           |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-VIII: | Perform Testing stage for above trained model and submitted to Kaggle.                                                |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-IX:   | Perform and Training using Feature Selection with GradientBoosting Regression with best parameters from Notebnook-VII |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
| Notebook-X:    | Perform Testing stage for above trained model and submitted to Kaggle.                                                |
+----------------+-----------------------------------------------------------------------------------------------------------------------+
```

Result:
```
+---------------------------------------------------------------+
| Features          | Model    | Test Score (Kaggle Submission) |
+-------------------+----------+--------------------------------+
| All Features      | RF Model | 0.19276                        |
+-------------------+----------+--------------------------------+
| Feature Selection | RF Model | 0.18691                        |
+-------------------+----------+--------------------------------+
| All Feature       | GD Model | 0.20075                        |
+-------------------+----------+--------------------------------+
| Feature Selection | GD Model | 0.15973                        |
+-------------------+----------+--------------------------------+
```
