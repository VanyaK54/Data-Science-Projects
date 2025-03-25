Here’s an improved and more engaging version of your "E-Commerce Product Delivery Prediction" project description:

---

# **E-Commerce Product Delivery Prediction**  
![](https://globalskylogistics.com/wp-content/uploads/2018/04/THE-CHANGING-NATURE-OF-E-COMMERCE-DELIVERY.jpg)  

## **Project Overview**  
The **E-Commerce Product Delivery Prediction** project focuses on predicting whether products from an international e-commerce company will reach customers on time. By analyzing key factors such as **shipment mode**, **warehouse block**, **product importance**, **customer behavior**, and **product weight**, the project provides valuable insights into the factors that influence delivery performance. The company primarily deals in **electronic products**, where timely delivery is crucial for maintaining **customer satisfaction** and **business reputation**.  

This project leverages machine learning techniques to build a predictive model that helps optimize logistics, reduce delays, and enhance customer service.  

---

## **Data Dictionary**  
The dataset contains **10,999 observations** across **12 variables**, capturing essential information about shipments and customer behavior:  

| **Variable**            | **Description**                                        |
|--------------------------|--------------------------------------------------------|
| **ID**                   | Unique identifier for each customer                    |
| **Warehouse_block**      | Warehouse location (A, B, C, D, E)                     |
| **Mode_of_Shipment**     | Shipment mode (Ship, Flight, Road)                     |
| **Customer_care_calls**  | Number of shipment inquiry calls made by the customer  |
| **Customer_rating**      | Customer satisfaction rating (1 - Lowest, 5 - Highest) |
| **Cost_of_the_Product**  | Product cost in US Dollars                             |
| **Prior_purchases**      | Total number of previous purchases by the customer      |
| **Product_importance**   | Product importance (Low, Medium, High)                 |
| **Gender**               | Gender of the customer (Male, Female)                  |
| **Discount_offered**     | Discount applied to the product (%)                     |
| **Weight_in_gms**        | Product weight in grams                                |
| **Reached.on.Time_Y.N**  | **Target Variable:** (1 - Delayed, 0 - On Time)        |

---

## **Key Insights from Exploratory Data Analysis (EDA)**  
In-depth analysis of the dataset revealed several crucial insights into the factors influencing delivery timeliness:  

### **1. Impact of Product Characteristics:**  
- **Weight & Cost:**  
  - Products weighing **2500–3500 grams** had a higher probability of **on-time delivery**.  
  - Lower-cost products (below **$250**) were more likely to arrive on time.  

- **Product Importance:**  
  - **High-importance** products had better on-time delivery rates, suggesting prioritization in the supply chain.  
  - **Low-importance** products faced more frequent delays.  

### **2. Warehouse & Shipment Mode Analysis:**  
- **Warehouse F** had the most shipments, with a significant portion sent via **ship**, indicating proximity to a **seaport**.  
- **Shipment Mode:**  
  - **Flights** had the shortest delivery times but were more expensive.  
  - **Road shipments** showed the highest frequency of delays.  

### **3. Customer Behavior:**  
- **Customer Care Calls:**  
  - Higher numbers of inquiry calls correlated with delayed deliveries, potentially indicating **service issues**.  
- **Prior Purchases:**  
  - Loyal customers (with more prior purchases) exhibited **higher on-time delivery rates**, reflecting potential prioritization.  
- **Customer Ratings:**  
  - Higher-rated customers generally experienced better service quality.  

### **4. Discount Analysis:**  
- Products with **0–10% discounts** were more likely to be delivered late.  
- **Higher discounts (above 10%)** correlated with improved delivery times, possibly due to promotional prioritization.  

---

## **Machine Learning Models — Building & Evaluation**  
To predict delivery timeliness, several classification models were developed and evaluated:  

| **Model**                | **Accuracy**        |
|---------------------------|--------------------|
| **Decision Tree Classifier** | **69%** |
| **Random Forest Classifier** | 68% |
| **Logistic Regression**     | 67% |
| **K-Nearest Neighbors (KNN)** | 65% |

✅ The **Decision Tree Classifier** outperformed other models with a **69% accuracy**, making it the most effective for this task.  

---

## **Impact and Real-World Applications**  
This project offers valuable insights for improving e-commerce logistics and customer satisfaction:  

- **Optimizing Delivery Routes:**  
  - Insights on shipment mode and warehouse efficiency can help streamline logistics.  
- **Customer Prioritization:**  
  - Loyal customers with high prior purchases can be prioritized for better service.  
- **Reducing Inquiry Calls:**  
  - Addressing service quality issues can reduce customer complaints and improve delivery performance.  
- **Dynamic Discount Strategies:**  
  - Offering strategic discounts can enhance timely delivery outcomes.  

---

## **Conclusion**  
The **E-Commerce Product Delivery Prediction** project demonstrates how **data-driven decision-making** can improve delivery performance in the e-commerce sector. By analyzing customer behavior, shipment methods, and product attributes, the project offers actionable insights for reducing delays and enhancing overall logistics efficiency.  

The **Decision Tree Classifier**, with its superior accuracy, serves as a reliable model for predicting delivery outcomes. Future work could involve integrating real-time tracking data and external factors (e.g., weather conditions) to further enhance prediction accuracy.  
