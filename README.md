# Credit Card Risk Analysis | EDA & Random Forest Classifier

A comprehensive machine learning project for predicting credit card approval using Random Forest Classifier with extensive Exploratory Data Analysis (EDA).

---

## 📊 Project Overview

This project develops a Random Forest Classifier to help banks make informed decisions about credit card approvals by analyzing applicant data and credit history. The model addresses the challenge of imbalanced datasets commonly found in credit risk assessment.

---

## 🎯 Problem Statement

Credit score cards are essential tools in the financial industry for predicting credit card defaults and guiding credit issuance decisions. This project aims to create an accurate predictive model using applicants' personal data and historical credit information to quantify risk objectively.

---

## 📁 Dataset Description

The project uses two main datasets:

### 📄 Application Record Dataset

- `ID`: Client number  
- `CODE_GENDER`: Gender  
- `FLAG_OWN_CAR`: Car ownership  
- `FLAG_OWN_REALTY`: Property ownership  
- `CNT_CHILDREN`: Number of children  
- `AMT_INCOME_TOTAL`: Annual income  
- `NAME_INCOME_TYPE`: Income category  
- `NAME_EDUCATION_TYPE`: Education level  
- `NAME_FAMILY_STATUS`: Marital status  
- `DAYS_BIRTH`: Age in days  
- `DAYS_EMPLOYED`: Employment duration  

### 📄 Credit Record Dataset

- `ID`: Client number  
- `MONTHS_BALANCE`: Record month  
- `STATUS`: Payment status (`0-5`: overdue periods, `C`: paid off, `X`: no loan)

---

## 🔧 Key Features

- **Data Preprocessing**: Comprehensive data cleaning, outlier removal, and feature engineering  
- **Exploratory Data Analysis**: In-depth analysis of relationships between variables  
- **Feature Selection**: VIF analysis to handle multicollinearity  
- **Model Building**: Random Forest Classifier optimized for imbalanced datasets  
- **Visualization**: Rich visualizations using matplotlib and seaborn  

---


## 🛠️ Technologies Used

- **Python 3.x**  
- `pandas` - Data manipulation  
- `numpy` - Numerical computations  
- `scikit-learn` - Machine learning  
- `matplotlib` & `seaborn` - Data visualization  
- `scipy` - Statistical analysis  

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn matplotlib seaborn scipy statsmodels
