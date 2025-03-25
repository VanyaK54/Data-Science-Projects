
# **Indian Used Car Price Prediction**  
![Used Car Price Prediction](http://cdn.dribbble.com/users/1239720/screenshots/3506944/car_mg.gif)  

## 📌 **Project Overview**  
The **Indian Used Car Price Prediction** project leverages **data analytics** and **machine learning** to estimate the prices of pre-owned cars across major **Indian metro cities**. The used car market in India is complex, with pricing influenced by factors such as:  
- **Manufacturer and model**  
- **Car age and kilometers driven**  
- **Fuel type and transmission**  
- **Body style and color preferences**  
- **Owner history and warranty availability**  

This project aims to assist **buyers**, **sellers**, and **dealers** by providing accurate price predictions, helping stakeholders make well-informed decisions.  

---

## 📊 **Dataset Information**  
The dataset used in this project, titled **"Indian IT Cities Used Car Dataset 2023,"** contains essential features for predicting used car prices.  

| **Column Name**       | **Description**                                   |
|------------------------|--------------------------------------------------|
| **ID**                 | Unique identifier for each car listing           |
| **Company**            | Car manufacturer (e.g., Maruti, BMW)             |
| **Model**              | Specific model name of the car                   |
| **Variant**            | Variant or trim level of the car                 |
| **Fuel Type**          | Type of fuel (Petrol, Diesel, CNG, Electric)     |
| **Color**              | Color of the car                                 |
| **Kilometer**          | Total kilometers driven by the car               |
| **Body Style**         | Type of body (Hatchback, SUV, Sedan, MPV)        |
| **Transmission Type**  | Type of transmission (Manual/Automatic)          |
| **Manufacture Date**   | Date the car was manufactured                     |
| **Model Year**         | Year the car model was released                  |
| **CNG Kit**            | Indicates whether the car has a CNG kit (Yes/No) |
| **Price**              | Actual sale price (Target Variable)              |
| **Owner Type**         | Number of previous owners (1st, 2nd, 3rd, etc.)  |
| **Dealer State**       | State where the car is being sold                |
| **Dealer Name**        | Name of the car dealer                           |
| **City**               | City where the car is being sold                 |
| **Warranty**           | Warranty offered by the dealer (Yes/No)          |
| **Quality Score**      | Overall quality score of the car                 |

---

## 🎯 **Objective**  
The primary goal of this project is to **predict the prices of used cars** accurately by leveraging historical data. The project intends to:  

- **Help buyers** assess the fair market value of a used car.  
- **Assist sellers** in setting competitive asking prices.  
- **Support dealers** in inventory pricing optimization.  
- **Enable investors** to identify undervalued vehicles for profitable resale.  

---

## 🏗️ **Project Workflow**  

1. **Data Preprocessing:**  
   - Handled missing values, outliers, and inconsistent data.  
   - Encoded categorical variables like **fuel type** and **body style**.  
   - Scaled numerical variables (e.g., **kilometers driven**).  

2. **Exploratory Data Analysis (EDA):**  
   - Analyzed demand and pricing trends.  
   - Explored the impact of fuel type, color preferences, and owner history on price.  
   - Identified key features driving car resale value.  

3. **Feature Engineering:**  
   - Created derived features such as **car age** and **price per kilometer**.  
   - Handled multicollinearity by selecting the most influential features.  

4. **Model Development:**  
   - Tested multiple regression models, including:  
     - **Linear Regression** for baseline performance.  
     - **Decision Tree Regressor** for model interpretability.  
     - **Random Forest Regressor** for handling non-linear relationships.  

5. **Model Evaluation:**  
   - Evaluated model performance using key metrics:  
     - **R² Score** — Measures how well the model explains variance.  
     - **Mean Absolute Error (MAE)** — Average prediction error.  
     - **Mean Squared Error (MSE)** — Penalizes larger errors more heavily.  
   - Used **cross-validation** to ensure generalization.  

---

## 📈 **Model Performance**  

| **Model**                  | **R² Score**    | **MAE**           | **MSE**            |
|----------------------------|----------------|--------------------|--------------------|
| **Linear Regression**       | 0.76           | 45,200 INR         | 2.1e+7             |
| **Decision Tree Regressor** | 0.83           | 32,100 INR         | 1.4e+7             |
| **Random Forest Regressor** | **0.88**       | **27,800 INR**     | **9.8e+6**          |

✅ The **Random Forest Regressor** demonstrated the best performance with an **R² score of 0.88**, making it ideal for accurate car price predictions.  

---

## 🔍 **Key Insights from EDA**  

1. **Demand & Price Trends:**  
   - **Budget-friendly cars** have higher demand compared to luxury cars.  
   - Luxury brands like **BMW**, **Mercedes-Benz**, and **Volvo** command the highest prices.  

2. **Fuel Type Impact:**  
   - **Diesel cars** are priced slightly higher than petrol cars.  
   - **CNG kit availability** boosts the market value of the vehicle.  

3. **Color Preferences:**  
   - **White, grey, silver, and black** are the most popular colors.  
   - Exotic colors like **burgundy** and **riviera red** fetch premium prices.  

4. **Kilometer Reading Impact:**  
   - Cars with **lower mileage (<10,000 km)** command significantly higher prices.  

5. **Body Style & Resale Value:**  
   - Hatchbacks, SUVs, and sedans are the most preferred body styles.  
   - MPVs and luxury SUVs command higher prices but cater to niche buyers.  

6. **Ownership & Warranty:**  
   - **First-owner cars** are in higher demand, fetching better resale value.  
   - Cars with a **warranty** are priced higher due to buyer assurance.  

---

## 🚀 **Impact and Real-World Applications**  

This project provides valuable insights for the **Indian used car market** by:  

- **Enabling buyers** to make data-driven purchase decisions.  
- **Helping sellers** price cars competitively.  
- **Assisting dealers** in inventory management and pricing optimization.  
- **Identifying undervalued cars** for profitable investment.  

---

## 🔮 **Future Scope**  

- **Integration of External Factors:**  
  - Adding market conditions, fuel prices, and economic data for better accuracy.  

- **Real-Time Price Estimation:**  
  - Developing a **web-based tool** for instant car price predictions.  

- **Explainable AI (XAI):**  
  - Using **SHAP** or **LIME** to understand feature importance in pricing.  

---

## ⚙️ **How to Run the Project**  

1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/your-username/used-car-price-prediction.git
   ```
2. **Navigate to the Project Directory:**  
   ```bash
   cd used-car-price-prediction
   ```
3. **Install Required Dependencies:**  
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the Project:**  
   ```bash
   python main.py
   ```