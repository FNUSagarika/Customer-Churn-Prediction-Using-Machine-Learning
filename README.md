# **Customer Churn Prediction Using Machine Learning**

This project analyzes customer behavior to predict churn using machine learning techniques. The aim is to help businesses identify at-risk customers and implement strategies to retain them.

Key highlights of this project:
  - Built and optimized a Decision Tree Classifier achieving 73% accuracy.
  - Conducted comprehensive data cleaning, preprocessing, and exploratory analysis.
---

## **Dataset**  
- Customer_Churn.csv, containing historical data of customers, each identified by a unique customer number.
- **Source:** [Kaggle](https://www.kaggle.com/datasets/willianoliveiragibin/customer-churn?resource=download)]  
- **Size:** 10,000 records with 13 features.  
- **Target Variable:** Exited column, indicating whether a customer has canceled their credit card (1 = churned, 0 = retained).  

### **Features:**
- **Demographics:** Customer ID, Surname, Gender, Age, Geography.  
- **Financial Details:** Credit Score, Balance, Estimated Salary.  
- **Engagement:** Tenure, Number of Products, Active Membership, Credit Card Status.  

---

## **Tools and Technologies Used**  
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Visualization:** Power BI  
- **Environment:** Jupyter Notebook  

---

## **Methodology**  

### **1. Data Preprocessing**  
- Removed irrelevant columns like `Customer ID` and `Surname`.  
- Handled missing values and standardized feature formats.  
- Encoded categorical variables (e.g., Gender, Geography).  

### **2. Exploratory Data Analysis (EDA)**  
- Analyzed patterns and trends across key features (e.g., churn rates by Geography or Age).  
- Visualized feature distributions and correlations using Matplotlib and Seaborn.  

### **3. Model Building**  
- Trained and optimized a **Decision Tree Classifier** for churn prediction.  
- Evaluated model performance using metrics: **Accuracy, Precision, Recall, F1-Score**.  

### **4. Visualization**   
- Churn rates by demographics and financial metrics.  
- Feature importance for customer churn prediction.  

---

## **Results**  
- **Model Accuracy:** 73%  
- **Key Findings:**  
 The most important features influencing customer churn are:
  - Estimated Salary: Customers with lower salaries are more likely to churn.
  - Credit Score: A low credit score correlates with higher churn risk. 
