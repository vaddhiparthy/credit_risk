# credit_risk
Credit Risk Evaluation using Machine Learning

## Abstract
The project aims to enable access to credit for individuals with limited or no credit histories using alternative data sources to assess their creditworthiness. The data like annual income, goods price (product for which loan is applied), the population of the client’s region, age of phone number, etc. were used to assess the creditworthiness. The data obtained is checked for the presence of inconsistent data that can interfere with the performance of the machine learning model using data visualization and exploratory data analysis techniques. Relevant features were identified by computing the correlation of all the features with the target variable which is a binary variable that indicates whether the individual has defaulted on credit repayments or not. Basic and advanced data wrangling techniques were used to fix the identified problems at various stages. Machine learning model evaluation techniques like cross-validation score, accuracy, confusion matrix, precision, and recall were used to evaluate the model’s ability in predicting the credit default variable. Basic data visualization techniques revealed that there are more female applicants, the applicant was unaccompanied at the time of loan application and a major proportion of the applicants were married. Further analysis of the data revealed that there is a class imbalance in the target variable i.e., the target variable had an unequal distribution of 0s and 1s which interfered with the Machine Learning model’s performance, and this was subsequently addressed by fixing the class imbalance. The model was recomputed to have 95% accuracy (f1-score) in predicting the target variable using extreme gradient boosting (XGBoost) Machine Learning algorithm after resolving the class imbalance using Synthetic Minority Over-sampling Technique. 

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

