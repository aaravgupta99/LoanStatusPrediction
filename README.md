
# Loan Status Prediction - Readme

In today's fast-paced financial world, lending institutions face numerous challenges in assessing the creditworthiness of loan applicants. The ability to accurately predict whether a borrower will default on a loan or successfully repay it can greatly impact the financial stability and profitability of these institutions.

The Loan Status Prediction project aims to address this challenge by leveraging the power of machine learning and predictive analytics. By analyzing historical data and applying advanced algorithms, we seek to develop a robust model that can predict the status of a loan application, specifically focusing on whether it will be approved or rejected on the basis of certain features to be sure that the applicant will not default.

## Dataset

 - [Loan Status Data](https://www.kaggle.com/datasets/ninzaami/loan-predication)

The project utilizes a created from many forms that were filled whenever an applicant applied for a loan.

These details of the form are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others.

The dataset is provided in CSV format and is split into a training set and a test set.
## Required Dependancies


| Dependancies | Version     | Description                |
| :-------- | :------- | :------------------------- |
| `Numpy` | 1.24.3 | **Optional**. For working with arrays |
| `Pandas` | 1.5.3 | **Required**. For dataframes and required process |
| `Seaborn` | 0.12.2 | **Required**. Advanced Data Visualization Techniques |
| `Sklearn` | 1.2.2 | **Required**. Model preprocessing, creation and evaluation |




## Workflow

**1. Data Retrieval** Using the data provided on kaggle.

**2. Data Preprocessing** Checking for missing values and removing if found. Dealing with the categorical data and converting them to numerical discrete type for the application of algorithm.

**3. Data Analysis** Identifying relationships between independant and dependant features.

**4. Train Test Split** Splitting the data into training dataset and testing dataset to train the machine learning model and evaluation.

**5. Model Creation and Training** Creating the appropriate machine learning model on the basis of type of data present.

**6. Evaluation** Evaluating the data on the basis of different metrics paramaters.


## Conclusion

The loan status prediction project will have far-reaching implications for both lending institutions and loan applicants. It has the potential to streamline loan processes, reduce financial risks, and improve access to credit for deserving individuals.