# Sweden Economic Analysis

## Project Overview

This project analyzes key economic indicators for Sweden, including GDP (current US$), Inflation (consumer prices, annual %), and Current Account Balance (% of GDP). The project incorporates data cleaning, exploratory data analysis (EDA), visualization, and basic machine learning models to predict economic trends. The project is designed to showcase data science and data analysis skills, with a focus on methods relevant to roles in Sweden.

## Sources

The data used in this project are directly collected from the World Bank website (https://data.worldbank.org/country/sweden).

- Data collection code [data_collection.ipynb](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/blob/main/data_collection.ipynb)
  1. It downloads world-wide data of,  
    (a) [Current account balance (% of GDP)](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/tree/main/API_BN.CAB.XOKA.GD.ZS_DS2_en_csv_v2_2788804),  
    (b) [Inflation, consumer prices (annual %)](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/tree/main/API_FP.CPI.TOTL.ZG_DS2_en_csv_v2_2789055),  
    (c) [GDP (current US$)](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/tree/main/API_NY.GDP.MKTP.CD_DS2_en_csv_v2_2788787),  
    (d) [Unemployment, total (% of total labor force)](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/tree/main/API_SL.UEM.TOTL.NE.ZS_DS2_en_csv_v2_2817174)  
  2. Extract data only relevant for Sweden and merged to create time-series in "[Sweden_data.csv](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/blob/main/Sweden_data.csv)".

- Data processing code [data_preprocessing.ipynb](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/blob/main/data_preprocessing.ipynb)
  1. Checking for and handling missing data.
  2. Checking for duplicate entries.
  3. Detecting and visualizing outliers using box plot.
  4. Saving the cleaned and preprocessed data in "[Sweden_data_preprossed.csv](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/blob/main/Sweden_data_processed.csv)".

- Exploratory data analysis code [eda.ipynb](https://github.com/arnobmukherjee1988/Swedish_Economic_Analysis/blob/main/eda.ipynb)
  1. Basis statistics.
  2. [Data trend]().
  3. [Correlation matrix]().
  4. [Scatter plot analysis]().
  5. [Histogram and distribution check]().
  6. [Box plot]().
  7. [Seasonality test]().


## Project Plan

### 1. Data Collection and Preparation (Day 1)

**Objectives:**
- Extract and prepare data for analysis.

**Steps:**
- **Extract Data for Sweden:**
  - Extract data for Sweden from the preprocessed dataset.
  - Focus on indicators such as GDP (current US$), Inflation (consumer prices, annual %), and Current Account Balance (% of GDP).
- **Data Cleaning:**
  - Ensure the datasets are clean, with no missing or anomalous values (already completed in preprocessing).
  - Align the data by year for consistent analysis across indicators (already completed).

### 2. Exploratory Data Analysis (EDA) (Day 2-3)

**Objectives:**
- Understand the data through visualizations and correlations.

**Steps:**
- **Trend Analysis:**
  - Plot each economic indicator over time to visualize long-term trends.
  - Identify significant economic events that correlate with changes in these indicators.
- **Correlation Analysis:**
  - Analyze correlations between GDP, inflation rate, and current account balance.
  - Use scatter plots and correlation coefficients to understand interdependencies.

### 3. Visualization (Day 4)

**Objectives:**
- Develop clear and insightful visualizations to present data trends.

**Steps:**
- **Time Series Plots:**
  - Create time series plots for GDP, inflation, and current account balance.
- **Combined Dashboard:**
  - Develop a dashboard that presents all three indicators together for comparison and analysis.
- **Interactive Plots (Optional):**
  - Create interactive visualizations using Plotly or Dash.

### 4. Basic Machine Learning Models (Day 5-6)

**Objectives:**
- Introduce and apply basic machine learning models to the data.

**Steps:**
- **Model Selection:**
  - **Linear Regression:**
    - Predict GDP based on inflation and current account balance.
  - **Decision Trees:**
    - Classify economic conditions (e.g., growth vs. recession) based on the indicators.
- **Model Training and Evaluation:**
  - Train the models using a portion of the data (e.g., 80% training, 20% testing).
  - Evaluate model performance using metrics like R² for regression and accuracy for classification.
  - Compare the models to assess their effectiveness.
- **Forecasting (Optional):**
  - Implement ARIMA or Prophet models to predict future trends in GDP, inflation, and current account balance.

### 5. Reporting and Presentation (Day 7)

**Objectives:**
- Compile and present findings in a professional format.

**Steps:**
- **Comprehensive Report:**
  - Write a detailed report summarizing trends, correlations, key insights, and findings from the machine learning models.
- **Executive Summary:**
  - Create an executive summary that highlights the most significant findings.
- **Update Portfolio Website:**
  - Add a new project page to your portfolio website featuring the report, key visualizations, and a summary of findings.
- **GitHub Repository:**
  - Push the cleaned data, analysis code, visualizations, and report to this GitHub repository.

## Tools and Libraries

- **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn (for machine learning), Statsmodels (for ARIMA), Prophet (for forecasting), Plotly/Dash (for interactive visualizations)
- **Jupyter Notebook:** For analysis and documentation
- **GitHub:** For version control and project sharing
- **Personal Website:** For showcasing the final project

## Deliverables

- **Dataset:** Cleaned and merged dataset with GDP, inflation, and current account balance for Sweden.
- **Visualizations:** Time series plots, correlation plots, and dashboard.
- **Machine Learning Models:** Basic models such as Linear Regression and Decision Trees.
- **Report:** A detailed report with insights and conclusions.
- **Portfolio Update:** Updated portfolio website with the project overview.
- **GitHub Repository:** This repository containing all relevant files.

## Timeline Summary

- **Day 1:** Data extraction, cleaning, and preparation.
- **Day 2-3:** Exploratory data analysis.
- **Day 4:** Visualization development.
- **Day 5-6:** Basic machine learning models (Linear Regression, Decision Trees) and forecasting (Optional).
- **Day 7:** Report writing, portfolio update, and project finalization.

## Progress Tracking

- [ ] **Day 1:** Data Collection and Preparation
- [ ] **Day 2-3:** Exploratory Data Analysis
- [ ] **Day 4:** Visualization Development
- [ ] **Day 5-6:** Basic Machine Learning Models
- [ ] **Day 7:** Reporting and Presentation

