# Energy-Consumption-Analysis
Analysis of PJM Hourly Energy Consumption Data

## Project Overview
This project analyzes the PJM Hourly Energy Consumption data to identify trends, patterns, and build predictive models. The analysis is performed individually for each region within the PJM Interconnection LLC, which serves parts of the Eastern United States.

## Dataset
- **Source**: PJM Interconnection LLC
- **Description**: Hourly power consumption data from PJM's website, measured in megawatts (MW). The data spans various regions and dates.
- **Files**:
  - `AEP_hourly.csv` (Completed)
  - `COMED_hourly.csv` (In Progress)
  - `DAYTON_hourly.csv` (In Progress)
  - `DEOK_hourly.csv` (In Progress)
  - `DOM_hourly.csv` (In Progress)
  - `DUQ_hourly.csv` (In Progress)
  - `EKPC_hourly.csv` (In Progress)
  - `FE_hourly.csv` (In Progress)
  - `NI_hourly.csv` (In Progress)
  - `PJME_hourly.csv` (In Progress)
  - `PJMW_hourly.csv` (In Progress)
  - `PJM_Load_hourly.csv` (In Progress)
  - `pjm_hourly_est.csv` (In Progress)

## Analysis Steps
### 1. Data Loading and Preprocessing
- Load the data for each region.
- Parse dates and handle missing values.
- Extract relevant features (Year, Month, Day, Hour, DayOfWeek).

### 2. Exploratory Data Analysis (EDA)
- **Energy Consumption Trends**:
  - Monthly, daily, and hourly trends.
- **Visualizations**:
  - Time series plots.
  - Average consumption by month, hour, and day of the week.
  - Heatmaps to show hourly trends across different days.
- **Observations**:
  - Higher energy consumption in January and February.
  - Peak consumption during evening hours (18:00 and 19:00).
  - Higher usage on weekdays (Tuesday, Wednesday, Thursday) compared to weekends.

### 3. Modeling
- **Objective**: Build a model to predict hourly energy consumption.
- **Features**: Month, Day, Hour, DayOfWeek.
- **Target**: AEP_MW (Energy Consumption in MW).
- **Model Used**: Linear Regression.

### 4. Evaluation
- **Metrics**: 
  - Mean Squared Error (MSE).
  - Root Mean Squared Error (RMSE).
- **Residual Analysis**:
  - Plot residuals to identify any patterns or anomalies.

### 5. Visualizations
- **Time Series Plot**: Energy consumption over time.
- **Monthly Trends**: Average consumption by month.
- **Hourly Trends**: Average consumption by hour.
- **Day of Week Trends**: Average consumption by day of the week.
- **Residual Plot**: Residuals of predictions over time.

## Key Findings for AEP Region
- **Monthly Trends**: January and February show higher energy consumption, likely due to heating needs in winter.
- **Hourly Trends**: Peak consumption occurs in the evening, around 18:00 and 19:00.
- **Weekly Trends**: Weekdays, especially Tuesday, Wednesday, and Thursday, have higher consumption compared to weekends.

## Future Work
- Complete the analysis for the remaining regions.
- Explore advanced modeling techniques (e.g., time series forecasting, machine learning models).
- Incorporate additional features such as weather data to improve predictions.


## Acknowledgments
PJM Interconnection LLC for providing the data.
Kaggle for hosting the dataset.
