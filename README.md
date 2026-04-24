
# 🚗 Accident Damage prediction & Data Analysis

## 📖 Overview
This project focuses on analyzing traffic accident data and building machine learning models to predict accident damage severity. The goal is to identify key factors affecting accidents and improve prediction accuracy for better decision-making.

---

## 🎯 Objectives
- Analyze accident data to identify key influencing factors  
- Clean and preprocess raw data for modeling  
- Apply machine learning algorithms for classification  
- Evaluate model performance and compare results  

---

## 📊 Dataset
- Original dataset: 20,008 records  
- After cleaning: 20,001 records  
- Features include: time, weather, injuries, crash type, road conditions, and more  

---

## 🛠️ Data Preprocessing
- Removed duplicates  
- Handled missing values using median imputation  
- Encoded categorical variables (Label Encoding + One-Hot Encoding)  
- Standardized numerical features using StandardScaler  

---

## 📈 Exploratory Data Analysis
Key insights:
- Most accidents occur in the evening  
- Intersections have higher severity accidents  
- Failing to yield is the most common cause  
- Weather and road conditions also influence accident severity  

---

## 🤖 Machine Learning Models
Two models were applied:
- K-Nearest Neighbors (KNN)  
- Logistic Regression  

### Results:
- Logistic Regression: 71% accuracy  
- KNN: 67% accuracy  
- Logistic Regression performed better in classification balance and stability  

---

## 📌 Conclusion
Machine learning can effectively help predict accident severity and identify key risk factors such as time, location, and driving behavior. Logistic Regression proved to be the most reliable model in this project.

