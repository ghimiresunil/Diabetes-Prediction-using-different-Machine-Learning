## 01. SHORT INTRODUCTION

Diabetes is a common chronic disease and poses a great threat to human health. The characteristic of diabetes is that the blood glucose is higher than the normal level, which is caused by defective insulin secretion or its impaired biological effects, or both. Diabetes can lead to chronic damage and dysfunction of various tissues, especially the eyes, kidneys, heart, blood vessels, and nerves. Diabetes can be divided into two categories, type 1 diabetes (T1D) and type 2 diabetes (T2D). Patients with type 1 diabetes are normally younger, mostly less than 30 years old.

The typical clinical symptoms are increased thirst and frequent urination, high blood glucose levels. This type of diabetes cannot be cured effectively with oral medications alone and the patients are required insulin therapy. Type 2 diabetes occurs more commonly in middle-aged and elderly people, which is often associated with the occurrence of obesity, hypertension, dyslipidemia, arteriosclerosis, and other diseases. So, let’s begin the project on Diabetes Prediction Using different machine learning algorithm.

## 02. DESCRIPTION

The objective of the project is to predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

Dataset url : https://www.kaggle.com/uciml/pima-indians-diabetes-database

## 03. FEATURE OBSERVATION

- There are a total of 768 records and 9 features in the dataset.
- Each feature can be either of integer or float dataype.
- Some features like Glucose, Blood pressure , Insulin, BMI have zero values which represent missing data.
- There are zero NaN values in the dataset.
- In the outcome column, 1 represents diabetes positive and 0 represents diabetes negative.

## 04. RESULT ON TESTING OF DIFFERENT MACHINE LEARNING MODEL

- **Logistic Regression**: 72.07792207792207
- **K Nearest neighbors**: 78.57142857142857
- **Support Vector Classifier**: 73.37662337662337
- **Naive Bayes**: 71.42857142857143
- **Decision tree**: 68.18181818181817
- **Random Forest**: 75.97402597402598

Note: From the above comparison, we can observe that K Nearest neighbors gets the highest accuracy of 78.57 %

## 05. INSTALLATION

- Clone this repository and unzip it.
- After downloading, cd into the flask directory.
- Begin a new virtual environment with Python 3 and activate it.
- Install the required packages using pip install -r requirements.txt
- Execute the command: python app.py
- Open http://127.0.0.1:5000/ in your browser.

## 06. SCREENSHOT

![01](https://user-images.githubusercontent.com/40186859/130610375-dbe4be70-7ed5-435f-893d-6b939e054765.png)
