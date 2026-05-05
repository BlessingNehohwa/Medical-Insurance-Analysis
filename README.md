# Medical-Insurance-Analysis

U.S. Medical Insurance Costs
🧾 Project Overview

This project explores a healthcare insurance dataset to uncover patterns in:

Patient demographics
Regional distribution
Impact of smoking on medical costs
Relationship between age and number of children
📦 Libraries Used
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
📂 Dataset Loading
insurance = pd.read_csv("Insurance data.csv")
🔍 Data Preview
insurance.head()
   age     sex     bmi  children smoker     region      charges
0   19  female  27.900         0    yes  southwest  16884.92400
1   18    male  33.770         1     no  southeast   1725.55230
2   28    male  33.000         3     no  southeast   4449.46200
3   33    male  22.705         0     no  northwest  21984.47061
4   32    male  28.880         0     no  northwest   3866.85520
📊 Statistical Summary
insurance.describe()
               age          bmi     children       charges
count  1338.000000  1338.000000  1338.000000   ...
📈 Key Analysis Areas
1. Age Distribution
Understanding how age varies across the dataset.
2. BMI Analysis
Examining body mass index trends and potential health implications.
3. Smoking Impact
Comparing medical charges between smokers and non-smokers.
4. Regional Insights
Identifying how location affects insurance costs.
5. Children vs Age
Exploring whether age influences number of dependents.
📉 Data Visualization

(Include your plots here if you generated any, e.g. matplotlib charts)

Example:

plt.hist(insurance['age'])
plt.title("Age Distribution")
plt.show()
💡 Key Insights
Smokers tend to have significantly higher medical charges.
BMI and age show moderate influence on insurance costs.
Regional differences exist but are less significant than smoking status.
🚀 How to Run
Clone this repository
Ensure you have Python installed
Install dependencies:
pip install pandas numpy matplotlib
Run your notebook or script
📌 Future Improvements
Add machine learning models for cost prediction
Perform feature engineering
Deploy as a dashboard (Power BI / Streamlit)
