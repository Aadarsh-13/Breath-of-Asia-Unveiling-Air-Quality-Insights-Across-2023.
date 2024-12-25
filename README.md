# Breath-of-Asia-Unveiling-Air-Quality-Insights-Across-2023.

This data analysis is based on region vise Air Quality Index (AQI)
# Grouped Line Chart of Countries' Average Monthly PM2.5 Concentration in East Asia
![image](https://github.com/user-attachments/assets/97d32c97-24aa-4576-a808-660758adee79)

"Explanation:"

Filter East Asia data: Create a DataFrame containing only East Asian countries.
Reshape data: Transform the data into a long format suitable for plotting.
Categorize months: Ensure the months are ordered correctly for plotting.
Group data: Calculate the average monthly PM2.5 concentrations for each country.
Plot data: Create a line chart with distinct colors for each country and display the visualization.


# AQI Levels
![image](https://github.com/user-attachments/assets/c8a909dd-2f66-4863-bab4-91da0b5b5a95)

Explanation:

Create DataFrame: Extract necessary columns and remove duplicates.
Count AQI Levels: Determine the number of countries in each AQI category.
Pie Chart: Visualize the percentage distribution of AQI levels across Asian countries.



![image](https://github.com/user-attachments/assets/179929ad-f303-4cc1-82e1-0708121caae9)

Explanation:
Data Preparation: Select monthly PM2.5 concentrations as features and average pollution as the target variable.
Train-Test Split: Split the data into training and testing sets.
Model Training: Initialize and train a linear regression model.
Model Evaluation: Evaluate the model using mean squared error and R-squared metrics.
Visualization: Plot actual vs predicted values to visualize the model's performance.


#Heat Map
![image](https://github.com/user-attachments/assets/042be4fa-5030-46d1-8866-53cafbc47948)

Explanation:
Pivot Data: Transform the data to have countries as rows and months as columns.
Plot Heatmap: Use Seaborn to create a heatmap of monthly PM2.5 concentrations.

#Forecasted values for a sample country (e.g., India)

![image](https://github.com/user-attachments/assets/3afa2831-002a-4f11-827b-2bdbdf6621dc)

Explanation:

Data Preparation: Calculate the average monthly PM2.5 concentrations for each country.
ARIMA Model: Initialize and fit the ARIMA model for each country's data.
Forecast Future Values: Forecast the PM2.5 concentrations for the next 12 months (1 year).
Visualize Forecast: Plot the forecasted values for a sample country (e.g., India).
