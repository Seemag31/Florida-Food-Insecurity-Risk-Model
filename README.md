# Florida Food Insecurity Risk Model


## Summary

This project investigated the relationship between access to basic resources (internet, vehicle, kitchen) and food insecurity rates across counties in Florida.


#### **Our goals were to:**

• Explore the socioeconomic factors influencing food insecurity.

• Classify counties into high-risk and low-risk groups based on food insecurity rates.

• Build a predictive model to estimate food insecurity risk based on accessibility factors. 
  
<br>

#### **Key Steps:**

**1. Data Selection**

**2. Data Collection and Cleaning:**

• Collected 2019–2022 socioeconomic data from the American Community Survey (ACS).
<br>


**3. Data Exploration:**

• Utilized scatterplots and histograms to visualize relationships between access variables and food insecurity rates.

• Ran a regressiona analysis to understand correlation of variables to food insecurity rates.

• Conducted a correlation analysis and a Variance Inflation Factor (VIF) test.

• Found that internet access and vehicle access are highly correlated (high VIF values), suggesting multicollinearity.
<br>

<br>

**4. Prediction Model:**

• Set a threshold for high/low food insecurity based on the mean plus standard deviation of the food insecurity rates.

• Classified counties accordingly to prepare labels for machine learning.

<br>

#### **Main Findings:**

• Internet access is a strong and statistically significant predictor of food insecurity risk.

• Vehicle access shows some relationship but overlaps heavily with internet access, so using only internet access improves model simplicity and reliability.

<br>

#### **Impact:**

• The study suggest that improving internet infrastructure may help mitigate food insecurity risks.

• The prediction model can help target interventions more effectively by identifying high-risk counties using simple, available socioeconomic data. More data is required to create a more accurate and reliable prediction model
