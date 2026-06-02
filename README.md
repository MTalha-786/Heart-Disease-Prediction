# Heart-Disease-Prediction
Build a model to predict whether a person is at risk of heart disease based on their health data. Dataset: Heart Disease UCI Dataset (available on Kaggle)

---

## **Heart Disease Prediction using Machine Learning**

### **Introduction**

This project focuses on predicting heart disease using a machine learning model. The dataset contains medical features such as age, cholesterol, blood pressure, and other health-related attributes. The goal is to classify whether a person has heart disease or not.

---

### **Steps Performed**

#### **1. Data Loading**

The dataset was loaded from Google Drive and converted into a Pandas DataFrame for analysis.

#### **2. Data Exploration**

Basic information about the dataset was checked, including:

* Shape of data
* Column names
* Data types
* Statistical summary
* Missing values
* Duplicate records

---

#### **3. Data Visualization**

A correlation heatmap was created to understand relationships between features and identify important variables.

---

#### **4. Feature Selection**

* **X (Features):** All input medical attributes
* **y (Target):** Heart disease result (0 or 1)

---

#### **5. Data Splitting**

The dataset was divided into:

* 80% training data
* 20% testing data

---

#### **6. Model Training**

A **Random Forest Classifier** was used to train the model. It is a powerful algorithm that builds multiple decision trees and combines their results.

---

#### **7. Model Evaluation**

The model was evaluated using:

* **Accuracy Score** to measure performance
* **Confusion Matrix** to analyze correct and incorrect predictions

---

#### **8. Feature Importance**

A bar chart was created to show which features contribute most to predicting heart disease.

---
---

