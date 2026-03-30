# PROJECT 7: TITANIC PREPROCESSING PROJECT

This project focuses on the essential steps of data preprocessing using the Titanic dataset. The goal is to prepare the raw data for machine learning tasks by handling missing values, encoding categorical features, and scaling numerical features.

## Project Overview

The following data preprocessing steps were performed:

1.  **Data Loading**: The Titanic dataset was loaded into a pandas DataFrame.
2.  **Data Cleaning**: Unnecessary columns like 'Cabin', 'Name', and 'Ticket' were dropped, as they were deemed not essential or contained too many missing values for this analysis.
3.  **Handling Missing Values**: Missing values in the 'Age' column were imputed using the median, and missing values in the 'Embarked' column were filled using the mode.
4.  **Feature Separation**: The dataset was split into input features (X) and the target variable (y), where 'Survived' is the target.
5.  **One-Hot Encoding**: Categorical input features ('Sex', 'Embarked') were converted into numerical format using one-hot encoding.
6.  **Label Encoding**: The target variable ('Survived') was label encoded.
7.  **Train-Test Split**: The dataset was divided into training and testing sets to evaluate model performance.
8.  **Standardization**: Numerical features in the training and testing sets were standardized using `StandardScaler`.
9.  **Normalization**: Numerical features were also normalized using `MinMaxScaler`.

## Summary of Steps

The project successfully covered the following topics:

1.  Data fetching from a GitHub CSV file.
2.  Initial data cleaning and inspection.
3.  Handling missing values.
4.  Applying One-Hot Encoding to categorical features.
5.  Applying Label Encoding to the target variable.
6.  Splitting data into training and testing sets.
7.  Applying Standardization to numerical features.
8.  Applying Normalization to numerical features.

This comprehensive preprocessing pipeline ensures that the data is well-prepared for any subsequent machine learning model training.
