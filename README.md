# Data Analytics for Insurance Cost

## Project Scenario
This is a practice project that involves performing data analytics on a medical insurance charges dataset. The dataset used is a filtered and modified version of the [Medical Insurance Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/medical-insurance-price-prediction?resource=download) dataset, available under the [CC0 1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/legalcode) on the [Kaggle](https://www.kaggle.com) website.

## Parameters
The parameters used in the dataset are:

### Age
Age of the insured. Integer quantity.

### Gender
Gender of the insured. This parameter has been mapped to numerical values in the following way.

|Gender|Assigned Value|
|------|--------------|
|Female|	    1       |
|Male	 |       2      |

### BMI
Body Mass Index of the insured. Float value quantity.

### No_of_Children
Number of children the insured person has. Integer quantity.

### Smoker
Whether the insured person is a smoker or not. This parameter has been mapped to numerical values in the following way.

|Smoker|	Assigned Value|
|------|--------------|
|Smoker|	1|
|Non smoker|	2|

### Region
Which region of the USA does the insured belong to. This parameter has been mapped to numerical values in the following way.

|Region|	Assigned Value|
|------|--------------|
|Northwest	|1|
|Northeast	|2|
|Southwest	|3|
|Southeast	|4|

### Charges
Charges for the insurance in USD. Floating value quantity.

## Objectives
- Load the data as a pandas dataframe.
- Clean the data, taking care of the blank entries.
- Run exploratory data analysis and identify the attributes that most affect the charges.
- Develop single variable and multi variable Linear Regression models for predicting the charges.
- Use Ridge regression to refine the performance of Linear regression models.
