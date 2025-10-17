
# Store Inventory Demand Analysis & Optimization

Welcome to the **Store Inventory Demand Analysis & Optimization** project, a repository created by **Yash Gadhave**.

This project focuses on leveraging **data-driven insights and advanced forecasting techniques** to streamline and optimize store inventory management. My goal was to enhance operational efficiency, significantly reduce costs, and guarantee optimal stock availability of essential supplies, specifically focusing on healthcare institutions. The solution seamlessly integrates **data analytics, statistical modeling, and optimization strategies**.

## Tools & Technologies Used:

  - **Python**
  - **Time Forecasting Models (ARIMA, Holt-Winters, VECM, Random Forest)**

## Key Achievements:

  - Successfully optimized product demand forecasting using **time series models** (ARIMA, Holt-Winters, VECM, and Random Forest), resulting in a **Mean Absolute Percentage Error (MAPE) below 10%** and a significant reduction in product shortages.
  - Developed a comprehensive **Excel-based inventory report** and automated **stock notifications using SQL**, which led to enhanced operational efficiency.
  - Built a **Power BI dashboard** to monitor and track sales performance, contributing to a **30% reduction in lost sales** and improved sales tracking capabilities.

## Table of Contents

1.  [Technical Overview](https://www.google.com/search?q=%23technical-overview)
2.  [Business Problem and Objectives](https://www.google.com/search?q=%23business-problem-and-objectives)
3.  [Data Preprocessing](https://www.google.com/search?q=%23data-preprocessing)
4.  [Exploratory Data Analysis (EDA)](https://www.google.com/search?q=%23exploratory-data-analysis-eda)
5.  [Forecasting Model](https://www.google.com/search?q=%23forecasting-model)
6.  [Project Challenges](https://www.google.com/search?q=%23project-challenges)
7.  [Future Scopes](https://www.google.com/search?q=%23future-scopes)
8.  [License](https://www.google.com/search?q=%23license)

## Technical Overview

My **Store Inventory Demand Analysis & Optimization** project combines robust data analytics and advanced forecasting techniques to deliver an optimized inventory management solution. Key technical components include:

### 1\. Data Collection and Analysis

I collected historical medical inventory data, covering consumption patterns, order quantities, and lead times. The data was meticulously cleaned using **Excel** and subjected to **Exploratory Data Analysis (EDA)** to identify underlying trends, seasonality, and irregularities.

### 2\. Forecasting Models

I implemented and compared several cutting-edge forecasting models to achieve the highest demand prediction accuracy:

  - **ARIMA** (AutoRegressive Integrated Moving Average) for focused time-series analysis.
  - **Holt-Winters** for exponential smoothing methods, capturing trend and seasonality.
  - **VECM** (Vector Error Correction Model) for multivariate time series forecasting.
  - **Random Forest** regression, a powerful machine learning model for predicting demand across multiple variables.

### 3\. Demand Variability Analysis

I conducted a deep dive into demand variability, specifically accounting for uncertainties like potential outliers and fluctuations in demand patterns. This analysis was crucial for informing the forecasting models and improving their overall robustness.

### 4\. Optimization Strategies

I developed and implemented practical strategies for optimal inventory management, including:

  - **Reorder Points**: Determining the precise, optimal point for stock replenishment to proactively prevent shortages.
  - **Order Quantities**: Calculating the most cost-efficient quantities to order based on projected demand and supplier lead times.

### 5\. Performance Metrics

I rigorously evaluated the forecasting models' performance using industry-standard metrics:

  - **Mean Absolute Error (MAE)**
  - **Mean Squared Error (MSE)**
    These metrics were instrumental in assessing model accuracy and guiding refinement for superior performance.

### 6\. Real-time Monitoring

The final models and optimization strategies were designed for implementation in a real-time system to continuously monitor inventory performance and validate the accuracy of predictions under actual business conditions.

-----

## Business Problem and Objectives

### Problem:

The core business issue I addressed was the persistent problem of **drug shortages** within healthcare institutions, which led to service disruptions, stockouts, and compromised service delivery. The overarching goal was to minimize these shortages to improve customer satisfaction and operational efficiency.

### Objectives:

  - **Minimize Drug Shortages**: Achieved through a focus on maximizing forecasting accuracy and optimizing inventory management processes.
  - **Maximize Drug Availability**: Ensuring that essential medical supplies are consistently available when and where they are needed, thereby enhancing patient care and customer satisfaction.

-----

## Data Preprocessing

Data preprocessing was a foundational and critical phase to ensure only high-quality data was used for analysis and forecasting. This involved:

### 1\. Data Cleaning

  - Identifying and correcting errors, inconsistencies, and missing values across the dataset.
  - Applying sophisticated **data imputation techniques** for missing data to ensure dataset completeness and integrity.

### 2\. Data Transformation

  - Transforming raw data into an appropriate format and scale that is suitable for various analysis or forecasting models.
  - Implementing **normalization techniques** to make the data more uniform and significantly improve model performance.

### 3\. Feature Engineering

  - Creating new, insightful variables based on the existing data (e.g., lag variables, rolling averages) to boost forecasting accuracy and model predictability.

-----

## Exploratory Data Analysis (EDA)

The **Exploratory Data Analysis (EDA)** phase involved a comprehensive examination of the data to uncover underlying trends, identify outliers, and establish patterns. Key EDA processes included:

### 1\. Data Distribution Analysis

  - Analyzing the distribution of demand data and identifying any skewness or irregular patterns that could affect modeling.

### 2\. Log Transformation

  - Applying **log transformations** to effectively normalize highly skewed data, making it more suitable for linear and time-series modeling.

### 3\. Visualizations

  - Creating informative histograms and bar plots to visually track quantities of drugs sold by month and quickly spot emerging trends.

### 4\. AutoEDA using D-Tale

  - I utilized **D-Tale**, an automated EDA tool, to gain deeper, accelerated insights into complex data patterns and relationships.

-----

## Forecasting Model

Accurately forecasting demand was the central focus of the project. I applied several forecasting models and assessed their performance based on prediction accuracy.

### Model Selection

  - **Random Forest Regression**: Chosen as a robust machine learning approach capable of handling complex, non-linear relationships in the demand data.
  - **Linear Regression**: Used as a baseline, simpler model for comparative analysis.

### Training and Testing

  - The historical data was meticulously split into training and testing datasets to rigorously assess model performance and ensure strong generalization to unseen, real-world data.

### Model Evaluation

I evaluated model performance using the following key metrics:

  - **Mean Squared Error (MSE)**
  - **Mean Absolute Percentage Error (MAPE)**

### Model Results

| Model | Metric | Value |
| :--- | :--- | :--- |
| **Holt-Winters Method** | RMSE | $5032.71$ |
| **Random Forest Regression** | MSE | $111.61$ |
| **Linear Regression** | MSE | $159.58$ |

The **Random Forest Regression** model consistently outperformed the other models in terms of accuracy, proving superior in capturing non-linear relationships and exhibiting higher stability with respect to data outliers.

-----

## Project Challenges

Throughout the execution of this project, I navigated several significant challenges:

  - **Stock Prediction with Return Quantities**: Incorporating return quantities into the inventory prediction model was complex and required additional, specialized modeling considerations.
  - **Privacy Concerns**: Ensuring absolute patient data privacy and meeting stringent regulatory standards was a critical, continuous task.
  - **New Drug Development**: Limited historical data for newly introduced drugs posed challenges in developing accurate demand forecasts.
  - **Regulatory Compliance**: Ensuring continuous compliance with pharmaceutical regulations and patient privacy laws (e.g., HIPAA) was paramount.
  - **Data Integration**: Successfully integrating external data sources and connecting them with existing, legacy inventory management systems proved challenging.
  - **External Factors**: Unforeseen market shifts, public health events, and other major disruptions impacted demand forecasting accuracy and required model adjustments.

-----

## Future Scopes

Looking ahead, the following areas represent exciting opportunities for continuous enhancement and expansion of the project:

### 1\. Enhanced Forecasting Models

  - Integrating more advanced machine learning techniques such as **deep learning** or **XGBoost** for potential marginal gains in prediction accuracy.
  - Incorporating additional, influential external factors like **seasonal trends**, real-time **health crises data**, and **global events** into the models for a more comprehensive forecasting picture.

### 2\. Supply Chain Optimization

  - Actively collaborating with suppliers and distributors to optimize the entire end-to-end supply chain, including analyzing **delivery routes** and implementing strategies for **reduced lead times**.
  - Integrating **real-time supply chain data** for dynamic, highly responsive forecasting adjustments.

### 3\. Machine Learning for Bounce Rate Reduction

  - Utilizing machine learning models to predict factors leading to, and ultimately reduce, high bounce rates in pharmacies by optimizing store layouts, minimizing returns, and enhancing overall customer experience.

-----
