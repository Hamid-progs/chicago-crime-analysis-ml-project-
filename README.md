# chicago-crime-analysis-ml-project-
A machine learning project for classifying and predicting crime types based on date, time, and location features.
# 🕵️‍♂️ Crime Type Classification using Machine Learning

## 📑 Project Overview
This project applies **machine learning classification techniques** to predict the **type of crime** based on features like **date, time, and location**.

**Objective:**  
Predict the type of crime (e.g., Theft, Assault) using machine learning based on **when** and **where** it happened.

---

## 📊 Dataset
The dataset contains cleaned crime data with columns such as:
- Date (date & time of crime)
- Latitude / Longitude (location)
- Primary Type (type of crime - target)
- Other metadata fields

### 📥 Features Used for ML:
- **Year**
- **Month**
- **Hour**
- **Latitude**
- **Longitude**

### 🎯 Target:
- **Primary Type** (Theft, Assault, Burglary, etc.)

---

## 🛠️ Technologies & Tools
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Scikit-learn  
- Folium (for map visualization)  
- Jupyter Notebook  

---

## 🚀 Project Workflow
1. **Data Cleaning & Preparation**
2. **Feature Engineering** (Extracting Year, Month, Hour)
3. **Exploratory Data Analysis (EDA)**
4. **Visualization** (Scatterplots, Heatmaps, Maps)
5. **Modeling** (RandomForestClassifier)
6. **Model Evaluation**
    - Accuracy
    - Confusion Matrix
    - Classification Report
