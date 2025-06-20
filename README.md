# **Heart Disease Prediction using Machine Learning**
## ## **Group Members**
1. Gathigi Moses Muiruri - gathimoses@gmail.com
2. odongo lsaiah - odongoreagan19@gmail.com
3. Keren Hapuch Ntinyari - karenhapuch68@gmail.com
4. Jebichii  Joyce - jebichiijoyce@gmail.com
5. Palpable Smart - palpable237@gmail.com
## **Project Overview**
This project aims to **predict the likelihood of heart disease** based on patient health data. By leveraging machine learning, healthcare professionals can use this system to assist in **early diagnosis and preventive care**.

## **🔹 Key Concepts Utilized**
### **Supervised Learning**
We employ **labeled health data** (like `heart.csv`) to train a classification model that distinguishes between patients with and without heart disease.

### **Data Preprocessing**
- Handle **missing values** (if any).
- Scale **numerical features** for better model performance.
- Encode **categorical data** to transform non-numeric variables.

### **Exploratory Data Analysis (EDA)**
- Utilize **visualization techniques** to detect **patterns in health metrics**.
- Generate **histograms, boxplots, and correlation heatmaps** for feature analysis.

### **Model Selection**
- Experiment with multiple classifiers:
  - **Logistic Regression**
  - **Random Forest**
  - **XGBoost**
- Optimize hyperparameters using **Grid Search or Random Search**.

### **Evaluation Metrics**
Assess model reliability using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-score**

---

## **🔹 Steps for Implementation in Jupyter Notebook**
### **1️⃣ Data Loading & Preprocessing 📝**
- Load `heart.csv` dataset.
- Clean missing values & encode categorical features.

### **2️⃣ Exploratory Data Analysis (EDA) 📊**
- **Histograms** for understanding feature distribution.
- **Boxplots** to detect outliers.
- **Correlation heatmaps** to analyze feature relationships.

### **3️⃣ Model Training & Evaluation 🤖**
- Train different **machine learning classifiers**.
- Evaluate **accuracy, precision, recall**, and **F1-score**.

### **4️⃣ Data Visualization 🎨**
- **Feature importance analysis**.
- **Confusion matrices** for model evaluation.
- **Receiver Operating Characteristic (ROC) curves**.

### **5️⃣ Deployability 🌍**
- Package the trained model for **real-world use** via:
  - **Flask API**
  - **Streamlit App**

---

## **🔹 Why This Matters?**
✅ **Early detection** of heart disease can save lives by enabling timely medical intervention.  
✅ AI democratizes healthcare by **providing accessible diagnostic tools**, particularly in **underserved regions**.

---

## **🔹 Additional Analysis of `heart.csv`**
The dataset consists of **various patient health attributes**, including:
- **Age**
- **Sex**
- **Chest Pain Type**
- **Cholesterol Levels**
- **Exercise Angina**
- **Max Heart Rate**
- **ST Slope**
- **Heart Disease Diagnosis**

### **Initial Observations**
- **Older patients** show higher chances of **HeartDisease = 1**.
- **Chest Pain Type (ASY)** is more frequent in patients diagnosed with heart disease.
- **Exercise Angina (Y)** is often associated with heart disease.
- **ST_Slope (Flat)** correlates with higher risk.
### **Summary of the prject**
https://colab.research.google.com/drive/1diWqE77LmvNzxkORUd5l7oiY1AnUgDoT?usp=sharing
### **Potential Improvements**
- **Feature Engineering**: Creating new features like **BMI** or **Risk Score**.
- **Advanced Models**: Exploring **Neural Networks** for deeper analysis.
