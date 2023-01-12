# credit_risk
Credit Risk Evaluation using Machine Learning

## Abstract
This undertaking aims to challenge the traditional credit assessment process by utilizing innovative alternative data sources to determine creditworthiness for individuals with limited or no credit history. The objective is to empower these individuals by providing them with access to credit.

The approach is to use diverse data points, such as annual income, product price, population demographics, and age of phone number, to accurately evaluate an individual's creditworthiness. Consistent data is meticulously checked for using advanced data visualization and exploratory data analysis techniques.

Relevant features are identified by conducting a detailed correlation analysis of all features with the target variable, a binary indicator of credit default. Advanced data wrangling techniques are also applied to fix any issues that may arise.

The ultimate goal is to build a machine learning model that can predict credit default with a high degree of accuracy. Advanced machine learning model evaluation techniques such as cross-validation scores, accuracy, confusion matrices, precision, and recall are utilized.

Data visualization revealed some interesting observations such as more female applicants, more single applicants, more married applicants, etc. Further data analysis showed the presence of a class imbalance in the target variable, which could negatively impact the performance of the machine learning model, so it was addressed by fixing the class imbalance.

By using Extreme Gradient Boosting (XGBoost) machine learning algorithm, a highly accurate model for predicting credit default was developed. This ambitious undertaking has the potential to transform the credit assessment process and provide previously underserved individuals with access to credit.

## Final Model
1. Extreme gradient boosting algorithm (XGBoost) after applying synthetic minority oversampling technique.
2. It was correct 98% of the time in identifying credit defaulters (precision).
3. It was able to identify 94% of the possible credit defaulters (recall).


## Conclusion and real-world reflections
1.	The best model (XGBoost with SMOTE) to identify the credit defaulter has been successfully identified using model evaluation metrics like precision and recall.
2.	Simplicity sometimes is preferred over accuracy due to regulatory compliances that require the model predictions to be interpretable and attributable to a specific feature, this would result in choosing an interpretable model over an accurate model.
3.	Privacy concerns related to gathering data for individuals with limited or no credit history where Adhoc data is used to assess the creditworthiness

## Future Scope
1.	Deploying the final ML model 
2.	Can model a continuous variable to generate a custom credit score.
3.	The use of Adhoc data from the bureau will further improvise the model
4.	A dynamic model based on geospatial information.
5.	Use of data scraped from bank statement

