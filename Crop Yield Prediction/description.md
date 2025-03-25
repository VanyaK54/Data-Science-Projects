# Crop Yield Prediction

<img src="https://img.in-part.com/resize?stripmeta=true&noprofile=true&quality=95&url=https%3A%2F%2Fs3-eu-west-1.amazonaws.com%2Fassets.in-part.com%2Ftechnologies%2Fheader-images%2F2aVv2twTYW9qZGGhPrxw_AdobeStock_241906053.jpeg&width=1200&height=820" width="700" height="500">

## Project Overview
The **Crop Yield Prediction** project utilizes data science techniques to forecast crop yields by analyzing various environmental and agricultural factors. The dataset includes metrics such as rainfall, temperature, fertilizer usage, and macronutrient levels (Nitrogen, Phosphorus, and Potassium), alongside corresponding crop yields measured in Quintals per acre. This predictive model aims to assist farmers and agricultural planners in optimizing resource allocation and maximizing crop output.

## Data Dictionary

| **Column Name**     | **Description**                                  |
|----------------------|--------------------------------------------------|
| **Rainfall (mm)**    | Total rainfall in millimeters.                   |
| **Temperature (°C)** | Average temperature in Celsius.                  |
| **Fertilizer (kg)**  | Amount of fertilizer used in kilograms.          |
| **Nitrogen (N)**     | Nitrogen macronutrient level.                    |
| **Phosphorus (P)**   | Phosphorus macronutrient level.                  |
| **Potassium (K)**    | Potassium macronutrient level.                   |
| **Yield (Q/acre)**   | Crop yield measured in Quintals per acre.        |

## Data Preprocessing

During preprocessing, several data quality issues were addressed:
- Invalid entries in the temperature column (represented by ":") were identified and removed.
- The temperature column was converted to a float data type for consistency.
- Missing values were imputed using the median of their respective columns to maintain data integrity.

## Exploratory Data Analysis (EDA)

Key insights derived from EDA include:
- **Crop Clusters:** Distinct clusters suggest the dataset may represent two different crop types with unique environmental conditions.
- **Fertilizer Impact:** Fertilizer usage generally correlates positively with crop yield, with some deviations.
- **Environmental Factors:** Temperature and rainfall patterns indicate seasonal variations affecting crop performance.
- **Macronutrient Distribution:** Variations in Nitrogen, Phosphorus, and Potassium levels reflect differing crop nutrient requirements.
- **Temperature Dominance:** Among all variables, temperature emerges as the most significant factor influencing crop yield, followed by rainfall.

## Model Building and Evaluation

Two machine learning regression models were developed and evaluated:
- **Decision Tree Regressor:** Achieved an R² score of **0.77**.
- **Random Forest Regressor:** Outperformed Decision Tree with an R² score of **0.802**.

The Random Forest Regressor demonstrated better generalization and predictive performance, underscoring the importance of ensemble methods in handling agricultural data.

## Conclusion

This study confirms that temperature is the most influential variable in crop yield prediction, with rainfall, fertilizer, and macronutrient levels also playing essential roles. The presence of two distinct crop clusters suggests differing environmental requirements. The Random Forest Regressor provides a reliable predictive model, but future research could explore additional variables, such as soil quality and pest impact, to enhance prediction accuracy and practical applicability.

