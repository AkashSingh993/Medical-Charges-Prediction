# Medical Charges Prediction

### Introduction

The goal is to predict medical charges (from an insurance dataset) based on various features of patients such as age, sex, BMI (Body Mass Index), number of children, smoking habits, and region. The model aims to predict the healthcare costs that future customers might incur based on historical data.

### Dataset
Dataset can be found on Kaggle [dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

### Methodology
a) Data Collection
The dataset was obtained from publicly available sources (Kaggle), containing records of individuals’ medical charges along with features like age, BMI, smoking status, and region.
b) Data Preprocessing
Handling Missing Values: Identified and addressed any missing data to ensure data integrity.

Encoding Categorical Variables: Converted categorical variables (e.g., "sex", "smoker", "region") into numerical format using one-hot encoding.

Feature Scaling: Applied standardization or normalization to numerical features like age and BMI to bring them into a common range.

Train-Test Split: Divided the dataset into training and testing sets (typically 80-20) for model evaluation.

c) Model Building
Implemented Linear Regression to predict medical charges based on available features, as it is well-suited for continuous target variables.

d) Model Evaluation
Root Mean Squared Error (RMSE): Assessed the model’s accuracy by measuring the average squared differences between predicted and actual values.
