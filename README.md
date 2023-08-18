# Heart-Attack-Prediction-Using-Different-ML-Models


## PROBLEM STATEMENT:
* A heart attack (Cardiovascular diseases) occurs when the flow of blood to the heart muscle suddenly becomes blocked. 
* From WHO statistics every year 17.9 million dying from heart attack. 
* The medical study says that human life style is the main reason behind this heart problem. 
* Apart from this there are many key factors which warns that the person may/maynot getting chance of heart attack.


## ABOUT PROJECT:
* In this project, we have used Heart Diseases Dataset from Kaggle for Heart Attack Prediction.
* This dataset contain some medical information of patients which tells whether that person getting a heart attack chance is less or more.
* Using the information, we explore the dataset and classify the target variable using different Machine Learning models to find out which algorithm is suitable for this dataset.



## ABOUT DATASET:

### Source : 
https://www.kaggle.com/code/heart-attack-prediction-using-different-ml-models

### Attribute Information : 
We use 13 input features and has 1 output variable:
* Age (Numerical) : age in years 
* Sex (Male /Female)
* chest pain type (4 values)
* resting blood pressure
* serum cholesterol in mg/dl
* fasting blood sugar > 120 mg/dl
* oldpeak = ST depression induced by exercise relative to rest
* maximum heart rate achieved
* resting electrocardiographic results (values 0,1,2)
* exercise induced angina
* the slope of the peak exercise ST segment
* number of major vessels (0-3) colored by fluoroscopy
* thal: 0 = normal; 1 = fixed defect; 2 = reversible defect
* target: 0= less chance of heart attack 1= more chance of heart attack


## ALGORITHM USED:
* Extreme Gradient Boost
* Support Vector Machine
* K-nearest Neighbours
* Random Forest
* Naive Bayes
* Logistic Regression
* Decision Tree

## CONCLUSION:
* Random Forest yields the highest accuracy of 88.524%
* Decision Tree yields the lowest accuracy of 81.967%
* Exercise-induced ST depression chest pain and increased heart rate are major symptoms of Heart attack.


