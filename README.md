#  Time Series Forecasting - Task 16

##  Objective
To analyze historical sales data and forecast future demand using time series techniques.

---

##  Tools Used
- Python (Google Colab)
- Pandas
- Matplotlib
- Statsmodels

---

##  Dataset
Retail Store Inventory Dataset

- Date
- Store ID
- Product ID
- Units Sold (used as Sales)

---

##  Steps Performed

### 1. Data Preprocessing
- Loaded CSV file
- Converted Date column to datetime format
- Set Date as index

### 2. Data Aggregation
- Aggregated data monthly using resample()

### 3. Data Visualization
- Plotted sales trend over time

### 4. Seasonality Check
- Applied rolling mean to identify patterns

### 5. Train-Test Split
- Split data into 80% training and 20% testing

### 6. Forecasting Model
- Used Exponential Smoothing model

### 7. Prediction
- Forecasted future values

### 8. Evaluation
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)

---

##  Results

- MAE: (add your value)
- MAPE: (add your value)

---

##  Output Files

- forecast_output.csv → contains actual vs predicted values
- forecast_report.txt → summary of model performance

---

##  Key Learnings

- Understanding time series data
- Importance of seasonality
- Forecasting techniques
- Model evaluation
