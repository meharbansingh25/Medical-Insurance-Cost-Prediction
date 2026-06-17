________________________________________
# Medical Insurance Cost Prediction 

---

## Tools Used

*	Python
*	NumPy
*	Pandas
*	Matplotlib
*	Seaborn
*	Scikit-learn
*	Jupyter Notebook

---

## Project Overview

This project analyzes raw medical insurance customer data and predicts insurance charges using machine learning techniques.

The project follows a complete end-to-end machine learning workflow including data quality checking, feature engineering, exploratory data analysis (EDA), NumPy statistical analysis, data preprocessing, model building, model evaluation, model interpretation, and business insight generation.

The objective is to identify the major factors affecting insurance costs and build an accurate prediction model.

---

## Dataset Information
The raw dataset contains customer demographic and health-related information such as:

* Age
* Gender
* BMI
* Number of Children
* Smoking Status
* Region
* Insurance Charges (Target Variable) 

---

## Feature Engineering
New features were created to improve customer analysis:

* **Age Group**
  * Young
  * Adult
  * Senior 

* **BMI Category**
  * Underweight
  * Normal
  * Overweight
  * Obese 

These engineered features helped provide deeper insights into customer health profiles and insurance cost patterns.

---

## Project Workflow

* Data Quality Check
* Feature Engineering
* Exploratory Data Analysis (EDA)
* NumPy Statistical Analysis
* Data Preprocessing
* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* Actual vs Predicted Analysis
* Model Comparison
* Model Interpretation
* Business Insights
* Final Conclusion 

---

## Libraries Used
* **Pandas** → Data analysis and manipulation
* **NumPy** → Statistical calculations and numerical operations
* **Matplotlib & Seaborn** → Data visualization
* **Scikit-learn** → Machine learning model development and evaluation 

---

## Machine Learning Models

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor 

---

## Model Performance

| Model                   |     MAE |    RMSE | R² Score |
| ----------------------- | ------: | ------: | -------: |
| Linear Regression       | 4407.45 | 6066.77 |     0.80 |
| Decision Tree Regressor | 2572.31 | 5653.86 |     0.83 |
| Random Forest Regressor | 2646.85 | 4679.53 |     0.88 |

---

## Model Interpretation
Machine learning interpretation revealed that the following factors had the greatest impact on insurance charges:

* **Linear Regression Coefficients**
  * Smoking Status
  * Obesity (BMI Category)
  * Age
  * Number of Children 

* **Random Forest Feature Importance**
  * Smoking Status
  * BMI
  * Age
  * Number of Children 

The Random Forest model confirmed that lifestyle and health-related factors have the strongest influence on medical insurance costs.

---

## Key Insights

* Smoking is the most significant factor increasing medical insurance charges.
* Customers with high BMI, especially obese individuals, generally have higher insurance costs.
* Age plays an important role in determining medical expenses.
* Gender and region have relatively lower impact compared with health-related factors.
* Random Forest achieved the best overall prediction performance with an R² Score of 0.88. 

---

## BMI vs Insurance Charges
![BMI vs Charges](https://github.com/meharbansingh25/Medical-Insurance-Cost-Prediction/blob/main/Medical%20Insurance%20Cost%20Prediction/Images/05_BMI_vs_Charges.png)

---

## Smoker vs Insurance Charges
![Smoker vs Charges](https://github.com/meharbansingh25/Medical-Insurance-Cost-Prediction/blob/main/Medical%20Insurance%20Cost%20Prediction/Images/08_Smoker_vs_Charges.png)

---

## Correlation Heatmap
![Correlation Heatmap](https://github.com/meharbansingh25/Medical-Insurance-Cost-Prediction/blob/main/Medical%20Insurance%20Cost%20Prediction/Images/14_Correlation_Heatmap.png)

---

## Actual vs Predicted Charges
![Actual vs Predicted Charges](https://github.com/meharbansingh25/Medical-Insurance-Cost-Prediction/blob/main/Medical%20Insurance%20Cost%20Prediction/Images/15_Actual_vs_Predicted.png)

---

## Model Comparison
![Model Comparison](https://github.com/meharbansingh25/Medical-Insurance-Cost-Prediction/blob/main/Medical%20Insurance%20Cost%20Prediction/Images/16_Model_Comparison.png)

---

## Random Forest Feature Importance
![Feature Importance](https://github.com/meharbansingh25/Medical-Insurance-Cost-Prediction/blob/main/Medical%20Insurance%20Cost%20Prediction/Images/18_Random_Forest_Feature_Importance.png)

---

# Conclusion

This project successfully transformed raw medical insurance data into meaningful insights using an end-to-end machine learning workflow.

Multiple regression algorithms were developed and evaluated, where Random Forest Regressor achieved the best performance with an R² Score of 0.88 and the lowest RMSE.

The analysis showed that smoking habits, BMI, and age are the most important factors influencing insurance charges.

Overall, this project demonstrates practical skills in raw data handling, feature engineering, exploratory data analysis, statistical analysis, machine learning, model interpretation, and business-oriented decision support.
