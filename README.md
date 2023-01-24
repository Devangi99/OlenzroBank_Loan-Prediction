

https://user-images.githubusercontent.com/88153883/214396009-b7b85f71-4a8a-40bd-8a61-4c4a70e34dda.mp4

# OlenzroBank_Loan-Prediction
This group project is related to the FDM module in 2nd semester of 3rd year. A Machine Learning model was developed to predict the risk of lending a loan to a customer, based on the related factors such as annual income, income category, age, house ownership, etc. . A historical data set from [Kaggle](https://www.kaggle.com/) was used as a source that contains important characteristics that were collected before lending the loan to customers. 

## Analyzing the dataset
- Step 01: Calculate the size of the dataset with number of features/attributes and check data types of the columns
![](images/s1.png)
- Step 02: Get an idea about columns and generate column names
![](images/s2.png)
- Step 03: Based on the observation of the dataset, plot a diagram to identify the correlation between the features
![](images/s3.png)

## Preprocessing data
- Step 01: Identify the null values in the dataset
![](images/pre1.png)
- Step 02: Handle numerical missing data with mean and check null values replaced or not
![](images/pre2.png)
- Step 03: Check duplicate values in the dataset
![](images/pre3.png)
- Step 04: Change the attribute values to a meaningful manner to maintain the consistency between the fields of the training dataset and user inputs
![](images/pre4.png)
- Step 05: Drop columns which are not related and less important
![](images/pre5.png)

## Visualizing data
- Step 01: Check whether the categorical default or not based on loan condition. Furthermore, check the features with respect to target 
![](images/v1.png)
- Step 02: Get the plots to get a clear idea about how the features affect to the loan condition
![](images/v2.png)
- Step 03: Check numerical data with loan condition and remove outliers
![](images/v3.png)
![](images/v3.1.png)
![](images/v3.2.png)

## Handling the categorical data with OneHotEncoding
![](images/onehotencoding.png)

## Model development
- Step 01: Separate independent and dependent variables
![](images/m1.png)
- Step 02: Split training and testing data set
![](images/m2.png)

## Model training
- Logistic Regression, Random Forest Classifier and Decision Tree Classifier were trained and compared. 
![](images/compare.png)

- The team decided to go with the Random Forest model
![](images/rfc.png)

- Feature importance 
![](images/fi.png)

## Model was deployed with Heroku
![](images/o_home.png)
![](images/o_form.png)
![](images/o_fill.png)
![](images/o_good.png)
![](images/o_bad.png)


## Tools & technologies
- Language - Python
- IDE - Jupyter, Visual	Studio	Code
- Framework - Flask
- Server/Hosting - Heroku

