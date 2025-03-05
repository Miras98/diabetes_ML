# 🩺 Diabetes Prediction Using Machine Learning  

## 📌 **Project Overview**  
This project aims to predict whether an individual has **diabetes** based on medical and demographic features. 
Using **machine learning classification algorithms**, 
we analyze patterns in patient data and build a predictive model to assist in early diagnosis.  

## 📊 Dataset Description  
The dataset contains several key medical features used to assess diabetes risk:  

| Feature | Description |
|---------|------------|
| `Pregnancies` | Number of times pregnant |
| `Glucose` | Blood glucose concentration |
| `BloodPressure` | Diastolic blood pressure (mm Hg) |
| `SkinThickness` | Triceps skinfold thickness (mm) |
| `Insulin` | 2-Hour serum insulin (mu U/ml) |
| `BMI` | Body Mass Index |
| `DiabetesPedigreeFunction` | Genetic predisposition to diabetes |
| `Age` | Age of the individual |
| `Outcome` | **Target Variable** (1 = Diabetes, 0 = No Diabetes) |

## 🎯 **Objective**  
The goal is to build a **classification model** that can predict whether a person has diabetes based on medical features. 
This can help in early detection and preventive healthcare strategies.  

## 🛠 **Technologies Used**  
- **Python** 🐍  
- **Pandas, NumPy** for data preprocessing  
- **Matplotlib, Seaborn,plotly** for visualization  
- **scikit-learn** for machine learning models  
- **Jupyter Notebook** for experimentation  

## 📊 **Exploratory Data Analysis (EDA)**  
- Checked for **missing values** and handled them  
- Analyzed **correlations between features**  
- Visualized **distribution of key variables**  
- Identified **outliers and anomalies**  

## 🤖 **Machine Learning Models Used**  
Several classification models were tested to find the best-performing one:  
✅ **Logistic Regression**  
✅ **Random Forest Classifier**  
✅ **Support Vector Machine (SVM)**  
✅ **K-Nearest Neighbors (KNN)**  

**Performance Metrics Evaluated:**  
- **Accuracy**
- **Precision, Recall, F1-score**
- **ROC-AUC Curve**

## 🚀 **Results & Findings**  
- The best model achieved **X% accuracy** on test data.  
- Feature importance analysis showed **Glucose and BMI** had the highest impact on predictions.  
- Imbalanced data was handled using **oversampling/undersampling techniques**.  
