# Belarus Car Price Prediction

![Belarus Car Market](https://i0.wp.com/bestsellingcarsblog.com/wp-content/uploads/2020/01/Geely-Atlas-Belarus-2019.jpg?fit=600%2C400&ssl=1)

## Project Overview
The **Belarus Car Price Prediction** project leverages machine learning techniques to forecast car prices in the Belarusian automotive market. Utilizing a dataset containing 56,244 rows and 12 essential features, this project aims to identify key variables that significantly influence car prices. Features such as make, model, year of production, mileage, fuel type, engine volume, and transmission type provide valuable insights into market dynamics, helping buyers and sellers make informed decisions.

## Data Dictionary

| **Variable**        | **Description**                                        |
|----------------------|--------------------------------------------------------|
| **make**            | Car manufacturer or brand.                             |
| **model**           | Specific model of the car.                             |
| **price USD**       | Price in US dollars (target variable).                 |
| **year**            | Year of production.                                    |
| **condition**       | Condition of the car at the time of sale.              |
| **mileage**         | Total distance traveled in kilometers.                 |
| **fuel type**       | Type of fuel (electric, petrol, diesel).               |
| **volume (cm³)**    | Engine volume in cubic centimeters.                    |
| **color**           | Exterior color of the car.                             |
| **transmission**    | Type of transmission (manual, automatic).              |
| **drive unit**      | Drive configuration (front-wheel, rear-wheel, AWD).    |
| **segment**         | Car market segment (luxury, specialty, economy).       |

## Key Insights
Exploratory data analysis (EDA) revealed several notable insights:
- **Post-2000 Price Surge:** Car prices in Belarus have seen a marked increase since the year 2000.
- **Fuel and Transmission Trends:**
  - Petrol cars with automatic transmission tend to have higher prices than diesel cars with manual transmission.
  - Electric cars stand out as significantly more expensive than other fuel types.
- **Drive Unit Impact:**
  - All-wheel-drive (AWD) vehicles command the highest prices among drive units.
- **Segment Hierarchy:**
  - Specialty segment cars lead in price, followed by luxury European, American, and Asian car segments.

## Model Building and Evaluation
For predictive modeling, a **Decision Tree Regressor** was employed to forecast car prices. The model achieved an impressive accuracy rate of **85.29%**, highlighting its effectiveness in capturing market trends.

### **Most Influential Features:**
- **Year of Production:** Older cars tend to depreciate, while newer models retain higher value.
- **Engine Volume:** Larger engine volumes are associated with higher prices due to performance preferences.

## Impact
This project offers valuable insights for buyers, sellers, and market analysts by identifying key factors that influence car pricing. The predictive model enables stakeholders to make data-driven decisions, optimizing their approach in a dynamic automotive market.

## Conclusion
The **Belarus Car Price Prediction** project demonstrates the power of machine learning in understanding market dynamics. By analyzing historical data and key features, this model helps in anticipating price trends, supporting better financial decisions for both buyers and sellers in Belarus.