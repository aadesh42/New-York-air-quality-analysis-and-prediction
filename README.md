# New-York-air-quality-surveillance
The project focuses on analyzing and predicting air quality in New York State using various machine learning models and time-series analysis techniques. Specifically, the goal is to evaluate trends in pollutants like PM 2.5 and Total SO2 emissions and build prediction models to forecast future pollution levels.
<br>
Dataset: The dataset contains data on different air quality indicators (e.g., PM 2.5, SO2 Emissions) across various geographic regions, with information on pollutant levels over time (Start_Date), geographic locations (Geo Place Name), and other features.
<br>
Data Preprocessing:
<br>
Data cleaning steps like handling missing values and converting date formats.
<br>
Feature engineering, such as extracting year and month from the Start_Date, and encoding categorical variables like Geo Place Name
<br>
Exploratory Data Analysis (EDA):
<br>
Identifying trends over time and comparing pollutant levels by year.
<br>
Visualizations such as line plots, bar plots, and box plots to assess air quality distribution across regions.
<br>
Modeling:
Several models were employed, including Random Forest, Linear Regression, and Gradient Boosting Regressor.
<br>
Evaluation:
Metrics such as Mean Squared Error (MSE), R-squared, and Cross-validation MSE were used to assess the model performance.
<br>
Outcome:
The final objective was to understand the trends in air quality and provide accurate future predictions to help in policymaking and environmental management.
<br>
Key Metrics in the Project:
<br>
Mean Squared Error (MSE): Measures the average squared difference between the predicted and actual values. Lower MSE indicates better model accuracy.
<br>
R-squared (R²): Indicates how well the model explains the variability of the target variable. A higher R² means the model is a good fit for the data.
<br>
Cross-Validation MSE: Evaluates the model's performance across different subsets of the data to ensure it generalizes well.
<br>
Success Criteria for the Project:
<br>
To determine if the project is successful, you can look at the following criteria:

Model Performance:

Achieving low MSE and high R-squared values indicate that the model is accurately predicting air quality.
Cross-validation MSE should also be low to ensure the model's robustness.
<br>
Accurate Predictions:

The forecasting models (like ARIMA and Prophet) should produce forecasts that are close to the actual future values of pollutants, with minimal error.
<br>
Trend Analysis:

The model should correctly identify significant trends in air quality, such as increasing or decreasing pollutant levels over time.
<br>
Actionable Insights:

If the analysis can provide actionable insights (e.g., identifying areas with worsening air quality, pinpointing seasonal variations in pollutants), then the project would be considered successful.
<br>
Visualization Effectiveness:

Clear and informative visualizations (line plots, bar charts, box plots) should effectively convey the air quality trends and make it easy to interpret the data.
<br>
Author- Aadesh Naik

