Here’s an improved version of your "Customer Churn Prediction" project description with a clearer structure and enhanced professionalism:

---

# **Customer Churn Prediction**  
![](https://miro.medium.com/v2/resize:fit:1400/1*47xx1oXuebvYwZeB0OutuA.png)  

## **Project Overview**  
The **Customer Churn Prediction** project focuses on identifying customers likely to leave a bank by analyzing demographic, financial, and behavioral data. Customer churn poses a significant challenge for banks, as losing valuable customers can adversely affect profitability. By building a robust predictive model, this project enables banks to take proactive measures to retain high-value customers, improve customer satisfaction, and boost overall business performance.  

---

## **Dataset Overview**  
The dataset, sourced from **Kaggle**, consists of **10,000 rows** and **14 columns**, capturing key attributes about bank customers. It includes demographic information, financial metrics, and behavioral indicators that may influence a customer's likelihood to churn. The target variable is labeled **"Exited"**, indicating whether a customer left the bank.  

---

## **Data Dictionary**  

| **Column Name**      | **Description**                                             |
|-----------------------|------------------------------------------------------------|
| **RowNumber**         | Row number (unique row index)                              |
| **CustomerId**        | Unique identification key for each customer                |
| **Surname**           | Customer's last name                                       |
| **CreditScore**       | Credit score of the customer                               |
| **Geography**         | Country of the customer                                    |
| **Age**               | Age of the customer                                        |
| **Tenure**            | Number of years the customer has been with the bank        |
| **Balance**           | Customer's bank balance                                    |
| **NumOfProducts**     | Number of bank products the customer is utilizing          |
| **HasCrCard**         | Binary flag indicating if the customer has a credit card (1 = Yes, 0 = No) |
| **IsActiveMember**    | Binary flag indicating if the customer is an active member (1 = Yes, 0 = No) |
| **EstimatedSalary**   | Estimated salary of the customer in USD                    |
| **Exited**            | Target variable — Binary flag where 1 = Customer churned, 0 = Customer retained |

---

## **Key Insights from Exploratory Data Analysis (EDA)**  
Through comprehensive data analysis, several key patterns emerged:  

- **Age and Credit Score**:  
  - Older customers and those with lower credit scores are more likely to churn.  
- **Geography**:  
  - Customers from certain countries exhibited higher churn rates.  
- **Balance and Products**:  
  - Customers with low or zero bank balance are more likely to leave.  
  - Customers with fewer bank products are more prone to churn.  
- **Customer Activity**:  
  - Inactive customers have a higher tendency to churn, regardless of other factors.  

---

## **Model Building and Performance**  
To predict customer churn, various machine learning models were implemented, including:  

- **Logistic Regression**  
- **Decision Tree Classifier**  
- **Random Forest Classifier**  
- **XGBoost Classifier**  

Among these, the **Random Forest Classifier** outperformed other models with the **highest accuracy**, effectively identifying high-risk customers.  

### **Performance Metrics:**  
- **Accuracy:** 85%  
- **Precision:** 82%  
- **Recall:** 80%  
- **F1-Score:** 81%  

---

## **Impact and Business Value**  
This predictive model empowers banks to:  
- **Proactively Retain Customers**: Identify at-risk customers and implement personalized retention strategies.  
- **Optimize Marketing Efforts**: Focus on high-priority customers likely to churn.  
- **Enhance Business Profitability**: Reduce customer acquisition costs by retaining existing customers.  

---

## **Conclusion**  
The **Customer Churn Prediction** project provides valuable insights into the factors influencing customer retention. By leveraging predictive modeling, banks can make data-driven decisions to reduce churn, improve customer satisfaction, and maximize profitability. Future work could involve incorporating additional behavioral data, such as transaction history, for even better predictive performance.  
