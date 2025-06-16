# Store Inventory Demand Analysis & Optimization

Welcome to the **Store Inventory Demand Analysis & Optimization** project on GitHub. This project is designed to optimize store inventory management by leveraging data-driven insights and advanced forecasting techniques. It integrates data analytics, statistical modeling, and optimization strategies to enhance efficiency, reduce costs, and ensure optimal stock availability of essential supplies in healthcare institutions.

## Tools Used: 
- **Excel**
- **SQL**
- **Power BI**
- **Python**
- **Time Forecasting Models (ARIMA, Holt-Winters, VECM, Random Forest)**

## Key Achievements:
- Optimized product demand forecasting with time series models like ARIMA, Holt-Winters, VECM, and Random Forest, achieving a MAPE under 10% and significantly reducing product shortages.
- Developed an Excel-based inventory report and automated stock notifications using SQL, enhancing operational efficiency.
- Created a Power BI dashboard to track sales performance, resulting in a 30% reduction in lost sales and enhanced sales tracking capabilities.

![image](https://github.com/mukul-bhele/inventoryoptimization/blob/a4bda0fed3e0286c622b06a977f45e524fd2ec90/Medical%20Inventory%20Optimization%20(Image).jpeg)

## Table of Contents
1. [Technical Overview](#technical-overview)
2. [Business Problem and Objectives](#business-problem-and-objectives)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Forecasting Model](#forecasting-model)
6. [Project Challenges](#project-challenges)
7. [Future Scopes](#future-scopes)
8. [License](#license)

## Technical Overview

The **Store Inventory Demand Analysis & Optimization** project combines data analytics and forecasting techniques to optimize inventory management. It includes the following components:

### 1. Data Collection and Analysis
Historical medical inventory data was collected, including information on consumption patterns, order quantities, and lead times. The data was cleaned using **Excel** and subjected to exploratory data analysis (EDA) to identify trends, seasonality, and irregularities.

### 2. Forecasting Models
We implemented several forecasting models to predict demand more accurately:
- **ARIMA** (AutoRegressive Integrated Moving Average) for time-series analysis.
- **Holt-Winters** for exponential smoothing methods.
- **VECM** (Vector Error Correction Model) for multivariate time series forecasting.
- **Random Forest** regression for predicting demand using multiple variables.

### 3. Demand Variability Analysis
We analyzed the variability of demand and accounted for uncertainties such as potential outliers and fluctuations in demand patterns. This analysis informed our forecasting models and helped improve their robustness.

### 4. Optimization Strategies
Developed strategies for optimal inventory management, which include:
- **Reorder Points**: Identifying the optimal point for replenishing stock to avoid shortages.
- **Order Quantities**: Calculating the most efficient quantities to order based on predicted demand and lead times.

### 5. Performance Metrics
We evaluated our forecasting models using several metrics:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
These metrics were used to assess model accuracy and refine the models for better performance.

### 6. Real-time Monitoring
The developed models and strategies were implemented in a real-time system to monitor inventory performance and validate the accuracy of predictions under actual business conditions.

## Business Problem and Objectives

### Problem:
The primary problem was the occurrence of drug shortages within healthcare institutions, leading to stockouts and compromised service delivery. Our goal was to minimize these shortages, which affect customer satisfaction and overall operational efficiency.

### Objectives:
- **Minimize Drug Shortages**: By optimizing forecasting accuracy and inventory management.
- **Maximize Drug Availability**: Ensuring that essential medical supplies are available whenever needed, improving patient care and customer satisfaction.

## Data Preprocessing

Data preprocessing was a critical phase of the project to ensure high-quality data for analysis and forecasting. This phase included the following steps:

### 1. Data Cleaning
- Identified and corrected errors, inconsistencies, and missing values in the dataset.
- Applied data imputation techniques for missing data to ensure completeness.

### 2. Data Transformation
- Transformed raw data into an appropriate format and scale suitable for analysis or forecasting models.
- Applied normalization techniques to make data more uniform and improve model performance.

### 3. Feature Engineering
- Created new variables based on the existing data to improve forecasting accuracy (e.g., lag variables, rolling averages).

## Exploratory Data Analysis (EDA)

The **Exploratory Data Analysis (EDA)** phase involved in-depth examination of the data to uncover trends, outliers, and patterns. Key aspects of the EDA process included:

### 1. Data Distribution Analysis
- Analyzed the distribution of demand data and identified any skewness or irregular patterns.

### 2. Log Transformation
- Applied log transformations to normalize highly skewed data, making it more suitable for modeling.

### 3. Visualizations
- Created histograms and bar plots to visualize quantities of drugs sold by month and spot any emerging trends.

### 4. AutoEDA using D-Tale
- Utilized **D-Tale**, an automated EDA tool, to gain deeper insights into data patterns and relationships.

## Forecasting Model

Forecasting demand accurately was the core of the project. We applied several forecasting models and assessed their performance based on prediction accuracy.

### Model Selection
- **Random Forest Regression**: A machine learning approach that handles complex, non-linear relationships.
- **Linear Regression**: A simpler model for comparison.

### Training and Testing
- Split the historical data into training and testing datasets to assess model performance and ensure generalization to unseen data.

### Model Evaluation
We used the following metrics to evaluate model performance:
- **Mean Squared Error (MSE)**
- **Mean Absolute Percentage Error (MAPE)**

### Model Results

1. **Holt-Winters Method**:
    - RMSE: 5032.71
2. **Random Forest Regression**:
    - MSE: 111.61
3. **Linear Regression**:
    - MSE: 159.58

The **Random Forest Regression** model outperformed the other models in terms of accuracy, capturing non-linear relationships and exhibiting higher stability with respect to outliers.

## Project Challenges

Throughout the project, we encountered several challenges:
- **Stock Prediction with Return Quantities**: Predicting inventory with return quantities was complex and required additional modeling considerations.
- **Privacy Concerns**: Ensuring that patient data remained private and met regulatory standards was critical.
- **New Drug Development**: Limited data on new drugs posed challenges in forecasting demand accurately.
- **Regulatory Compliance**: Ensuring compliance with pharmaceutical regulations and patient privacy laws was a continuous task.
- **Data Integration**: Integrating external data sources and connecting them with existing inventory management systems was challenging.
- **External Factors**: Market shifts, public health events, and unforeseen disruptions impacted demand forecasting accuracy.

## Future Scopes

Looking ahead, the following areas present exciting opportunities for project enhancement:

### 1. Enhanced Forecasting Models
- Integrating more advanced machine learning techniques such as **deep learning** or **XGBoost** for improved prediction accuracy.
- Incorporating additional factors like **seasonal trends**, **health crises**, and **global events** into the models for more comprehensive forecasting.

### 2. Supply Chain Optimization
- Collaborating with suppliers and distributors to optimize the entire supply chain, including **delivery routes** and **reduced lead times**.
- Integrating **real-time supply chain data** for dynamic forecasting.

### 3. Machine Learning for Bounce Rate Reduction
- Using machine learning models to predict and reduce high bounce rates in pharmacies by optimizing store layouts, reducing returns, and enhancing customer experience.

## License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

Thank you for exploring the **Store Inventory Demand Analysis & Optimization** project on GitHub. Your contributions, feedback, and collaboration are highly valued. If you have any questions or would like to get involved, please reach out to me.

