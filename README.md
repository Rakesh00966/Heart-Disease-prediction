# ❤️ Heart Disease Prediction using Machine Learning [LINK](https://github.com/Rakesh00966/Heart-Disease-prediction/blob/main/Heart_Disease_prediction.ipynb)

This project aims to **predict the presence of heart disease** in patients based on various medical attributes.  
It demonstrates the complete **machine learning workflow** — from **data understanding** and **exploration** to **model building, evaluation**, and **prediction** on unseen data.

---

## 📊 Dataset Overview

The dataset contains **270 records** with **13 medical features** and one target variable `Heart Disease`.

| Feature | Description |
|----------|-------------|
| **Age** | The person’s age in years |
| **Sex** | The person’s sex (1 = male, 0 = female) |
| **Chest pain type** | (1 = typical angina, 2 = atypical angina, 3 = non-anginal pain, 4 = asymptomatic) |
| **BP** | Resting blood pressure (mm Hg) |
| **Cholesterol** | Serum cholesterol level (mg/dl) |
| **FBS over 120** | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false) |
| **EKG results** | Resting electrocardiographic results (0 = normal, 1 = ST-T abnormality, 2 = LVH) |
| **Max HR** | Maximum heart rate achieved |
| **Exercise angina** | Exercise induced angina (1 = yes; 0 = no) |
| **ST depression** | Depression induced by exercise relative to rest |
| **Slope of ST** | The slope of the peak exercise ST segment (1 = upsloping; 2 = flat; 3 = downsloping) |
| **Number of vessels fluro** | Number of major vessels (0–3) colored by fluoroscopy |
| **Thallium** | Thallium stress test (3 = normal; 6 = fixed defect; 7 = reversible defect) |
| **Heart Disease** | Target variable (Presence / Absence) |

---

## 🧠 Workflow Summary

### 1️⃣ Data Understanding
- Loaded and inspected dataset using **pandas**
- Checked datatypes, null values, and descriptive statistics

### 2️⃣ Exploratory Data Analysis (EDA)
- Visualized key feature distributions using **Seaborn** and **Matplotlib**
- Studied correlation between features and the target variable

### 3️⃣ Data Preprocessing
- Encoded the target variable (`Heart Disease`) using **LabelEncoder**
- Scaled numerical features using **StandardScaler**
- Split data into training and test sets (80:20)

### 4️⃣ Model Building
Trained multiple ML algorithms for comparison:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Gaussian Naive Bayes  
- Decision Tree Classifier  
- Random Forest Classifier  

### 5️⃣ Model Evaluation
Metrics used:
- **Accuracy**
- **Precision**
- **Recall**
- **ROC AUC**
- **Confusion Matrix**

### 6️⃣ Model Comparison
Visualization of performance metrics for all models using bar charts.

---

## 🏆 Model Performance Summary

| Model | Accuracy | Precision | Recall | ROC AUC |
|--------|-----------|------------|---------|----------|
| Logistic Regression | 0.90 | 0.90 | 0.86 | 0.90 |
| Gaussian Naive Bayes | 0.90 | 0.94 | 0.81 | 0.89 |
| Support Vector Machine | 0.88 | 0.89 | 0.81 | 0.87 |
| Random Forest Classifier | 0.87 | 0.94 | 0.71 | 0.84 |
| K Nearest Neighbors | 0.81 | 0.82 | 0.66 | 0.78 |
| Decision Tree Classifier | 0.68 | 0.57 | 0.71 | 0.69 |

🩺 **Best Model:** Logistic Regression (Highest Accuracy and Balanced Metrics)

---
