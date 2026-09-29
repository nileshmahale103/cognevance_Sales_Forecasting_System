# Sales Forecasting System

## 1. Project Overview

The Sales Forecasting System is a Data Analytics and Machine Learning project developed to analyze historical sales data and predict future sales.

This project uses Python, Pandas, NumPy, Matplotlib, and Linear Regression to analyze sales trends, evaluate model performance, and forecast sales for the next three months.

A Power BI dashboard is also developed to visualize sales performance and present meaningful business insights.

This project was developed as part of the Data Science and Data Analytics Internship at Cognevance Technologies.

## 2. Project Objectives

The main objectives of this project are:

* To analyze historical sales data and identify sales trends.
* To clean and preprocess the dataset for accurate analysis.
* To develop a machine learning model for sales forecasting.
* To predict sales for the next three months.
* To evaluate model performance using MAE and RMSE.
* To create a Power BI dashboard for business insights.
* To support data-driven business planning and decision-making.

## 3. Technologies Used

| Technology      | Purpose                                |
| --------------- | -------------------------------------- |
| Python          | Data analysis and model development    |
| Pandas          | Data cleaning and manipulation         |
| NumPy           | Numerical calculations                 |
| Matplotlib      | Data visualization                     |
| Scikit-learn    | Linear Regression and model evaluation |
| Google Colab    | Writing and executing Python code      |
| Power BI        | Sales dashboard and visualization      |
| Microsoft Excel | Dataset management                     |

## 4. Dataset Description

The project uses a sales dataset containing 6,000 records and 13 columns.

The dataset includes sales-related information such as order dates, sales amounts, product details, and other business attributes.

**Dataset Period:** January 2025 to September 2026

The dataset was cleaned and processed before performing exploratory data analysis and sales forecasting.

## 5. Project Workflow

### Step 1: Data Collection

The sales dataset was imported into Google Colab using Python for analysis.

### Step 2: Data Cleaning and Preprocessing

The dataset was checked and prepared for analysis. Date-related and sales-related columns were processed, and the data was organized for further calculations.

### Step 3: Exploratory Data Analysis (EDA)

Historical sales data was analyzed to understand monthly sales trends and identify patterns in business performance.

### Step 4: Model Development

A Linear Regression model was developed using historical monthly sales data to predict future sales.

The data was divided into training and testing sets to evaluate the model's performance.

### Step 5: Model Evaluation

The model was evaluated using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

### Step 6: Sales Forecasting

The trained model was used to forecast sales for October, November, and December 2026.

### Step 7: Dashboard and Business Insights

A Power BI dashboard and a business insights report were prepared to present the analysis and forecasting results in an understandable format.

## 6. Model Performance

The Linear Regression model was evaluated on the test dataset.

| Evaluation Metric              |    Result |
| ------------------------------ | --------: |
| Mean Absolute Error (MAE)      | 30,114.83 |
| Root Mean Squared Error (RMSE) | 42,196.11 |

**MAE:** Measures the average absolute difference between actual and predicted sales.

**RMSE:** Measures prediction errors while giving more weight to larger errors.

These results provide an estimate of the model's forecasting error on the test data.

## 7. Sales Forecast Results

The model generated the following sales forecasts:

| Month         | Predicted Sales |
| ------------- | --------------: |
| October 2026  |      134,830.39 |
| November 2026 |      134,347.80 |
| December 2026 |      133,865.22 |

These values are model-generated estimates based on historical sales patterns and are not guaranteed actual sales.

## 8. Business Insights

The project helps businesses to:

* Understand historical sales performance.
* Observe monthly sales trends.
* Estimate future sales and support business planning.
* Make data-driven decisions using historical information.
* Monitor sales performance through a Power BI dashboard.

## 9. Project Files

| File                                              | Description                                                                              |
| ------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| `Sales_Forecasting_Dataset.xlsx`                  | Dataset used for sales analysis                                                          |
| `Sales_Forecasting_Analysis_Final (1).ipynb`      | Python notebook containing data analysis, model development, evaluation, and forecasting |
| `Sales_Forecasting_Dashboard.pbix`                | Power BI sales dashboard                                                                 |
| `Sales_Forecasting_Business_Insights_Report.docx` | Business insights and analysis report                                                    |
| `sales_forecast_next_3_months.csv`                | Forecast results for the next three months                                               |
| `sales_forecast_test_evaluation (1).csv`          | Model evaluation results                                                                 |

## 10. How to Run the Project

1. Download the project files from the repository.
2. Open Google Colab.
3. Upload the Jupyter Notebook and the sales dataset.
4. Run the notebook cells in sequence.
5. Review the data analysis, model evaluation, and forecast results.
6. Open the Power BI dashboard using Power BI Desktop.

## 11. Future Scope

The project can be improved in the future by:

* Using advanced time-series forecasting algorithms.
* Incorporating additional sales data for better analysis.
* Improving forecasting accuracy through model comparison.
* Developing an interactive web-based sales forecasting application.
* Automating the process of updating forecasts with new sales data.

## 12. Internship Information

**Organization:** Cognevance Technologies

**Internship Domain:** Data Science and Data Analytics

**Project Title:** Sales Forecasting System

**Project Level:** Level 2

## Author

**Nilesh Mahale**
