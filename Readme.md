# 🎧 Audiobook Customer Conversion Prediction  

## 📖 Overview  
This project focuses on building a machine learning model to predict whether customers of an audiobook app will make repeat purchases. By leveraging data-driven insights, the goal is to help the audiobook company optimize its advertising budget by targeting customers who are likely to convert again. Identifying these customers not only helps in refining marketing strategies but also improves overall customer retention and profitability.  

---

## 🧩 Problem Statement  
The audiobook app collects data about its customers, including engagement metrics and purchasing behavior. The challenge is to predict whether a customer will buy again based on historical data.  

**Key Objectives:**  
1. 🧠 Predict customer conversion (repeat purchase) using machine learning.  
2. 📊 Identify important factors that influence customer retention and engagement.  
3. 🚀 Provide actionable insights to improve sales and profitability.  

---

## 📂 Data Description  
The dataset includes the following features:  
- **📚 Book Length (Overall & Average):** Total and average duration of purchased audiobooks.  
- **💵 Price Paid (Overall & Average):** Total and average cost of purchases.  
- **⭐ Review:** Boolean indicating if a customer left a review.  
- **📈 Review Rating:** Average review score (missing values replaced by 8.91, the dataset average).  
- **⏳ Total Minutes Listened:** Engagement metric indicating total listening time.  
- **🎯 Completion Ratio:** Ratio of minutes listened to the total book length.  
- **📩 Support Requests:** Number of customer support requests submitted.  
- **📆 Engagement Duration:** Time between the first purchase and the last interaction with the platform.  
- **🏷️ Target Variable:** Boolean indicating conversion (1 for repeat purchase, 0 otherwise).  

The dataset contains two years of customer data, with an additional six months of data used to define the target variable.  

---

## 🛠️ Workflow  
1. **⚙️ Data Preprocessing**  
   - Balance the dataset to address class imbalance.  
   - Divide the dataset into training, validation, and test sets.  
   - Save the processed data in a TensorFlow-friendly `.npz` format for easy access.  

2. **🧠 Model Development**  
   - Create a deep learning model using TensorFlow.  
   - Train the model using the processed dataset.  
   - Evaluate the model's performance on the test data.  

3. **♻️ Code Reusability**  
   - Build reusable functions and classes for data preprocessing and batching.  
   - Provide a modular pipeline for future applications on similar datasets.  

---

## 🎯 Results  
The model predicts whether a customer will make a repeat purchase with accuracy and provides insights into the most important features influencing customer behavior.  

---

## 🌟 Key Learnings  
- 🛠️ The importance of preprocessing real-world data for machine learning.  
- ⚖️ Handling imbalanced datasets for better predictive performance.  
- 🤖 Using TensorFlow for building and training deep learning models.  

---
## 🛠️ Dependencies  
- 🐍 Python 3.x  
- 🔧 TensorFlow  
- 📊 NumPy  
- 📝 Pandas 

---

## 🙌 Credits
This project is inspired by the practical application of machine learning in business contexts and was developed as part of a data science course.
