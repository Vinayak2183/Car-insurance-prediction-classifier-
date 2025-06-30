#  Car Insurance Claim Prediction - Mini Project

This project aims to predict whether a customer will file a car insurance claim using machine learning. The main model used in this project is the **Random Forest Classifier**.

---

##  Objective

To process and analyze car insurance customer data and build a machine learning model that can predict insurance claim behavior effectively.

---

##  Dataset Overview

The dataset includes a variety of customer and vehicle attributes. The target variable is:

- **Car_Insurance_Claim**: `1` if the customer filed a claim, `0` otherwise.

### Key Features:

- Age  
- Gender  
- Driving Experience  
- Education  
- Income  
- Vehicle Ownership  
- Vehicle Year  
- Married  
- Children  
- Annual Mileage  
- Speeding Violations  
- DUIs  
- Past Accidents  
- Vehicle Type  

---

##  Exploratory Data Analysis (EDA)

- Visualized feature distributions using count plots and histograms
- Plotted class balance of the target variable
- Used heatmaps to check feature correlations

---

##  Data Preprocessing

- Handled categorical data using:
  - **Label Encoding** for binary categorical features
  - **One-Hot Encoding** for multi-category features
- Standardized numerical features using `StandardScaler`
- Split dataset into training and test sets (80%-20%)

---

##  Model Used

###  **Random Forest Classifier**

- Trained on the preprocessed dataset
- Evaluated using accuracy and classification metrics

###  Model Performance:

- **Accuracy Score**: **91.22%**
- **Classification Report**: Shows high precision, recall, and F1-score
- **Confusion Matrix**: Visualized to interpret performance
- **ROC-AUC Curve**: Plotted to assess model discrimination capability

---

## Test Set Result are in its csv 
