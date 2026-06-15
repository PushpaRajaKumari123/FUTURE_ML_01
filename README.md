# FUTURE_ML_01 - Sales & Demand Forecasting Using Machine Learning

## Objective

The objective of this project is to forecast future sales using historical sales data and Machine Learning techniques. Accurate sales forecasting helps businesses make informed decisions related to inventory management, demand planning, and resource allocation.

---

## Dataset

**Dataset Used:** Sample Superstore Dataset

* Total Records: 9,994
* Features: 21 columns including:

  * Sales
  * Profit
  * Quantity
  * Category
  * Region
  * Order Date
  * Customer Information
  * Shipping Details

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

---

## Project Workflow

### 1. Data Collection

* Loaded the Sample Superstore dataset.
* Explored dataset structure and feature information.

### 2. Data Preprocessing

* Converted **Order Date** to datetime format.
* Checked and handled missing values.
* Removed duplicate records.
* Prepared data for analysis and modeling.

### 3. Exploratory Data Analysis (EDA)

* Analyzed sales trends over time.
* Visualized sales distribution and patterns.
* Identified trends and business insights using graphical representations.

### 4. Model Building

* Applied **Linear Regression** for sales forecasting.
* Performed train-test split.
* Trained the model using historical sales data.

### 5. Prediction & Forecasting

* Generated sales predictions on test data.
* Compared actual and predicted sales values.
* Forecasted future sales for the next 30 days.

---

## Results

* Successfully trained a Linear Regression model.
* Generated Actual vs Predicted Sales visualizations.
* Created future sales forecasts based on historical trends.
* Evaluated model performance using standard regression metrics.

---

## Business Impact

This project can help organizations:

* Improve inventory planning.
* Support demand forecasting.
* Enable data-driven decision-making.
* Reduce the risk of stock shortages and overstocking.
* Enhance operational efficiency.

---

## Repository Contents

```text
FUTURE_ML_01/
│
├── FUTURE_ML_01.ipynb
├── sales_trend_overtime.png
├── actual_vs_predicted_sales.png
├── future_sales_forecast.png
└── README.md
```

---

## Future Enhancements

* Implement advanced forecasting models such as Random Forest Regressor and XGBoost.
* Incorporate seasonal and trend-based features.
* Improve forecasting accuracy with additional business variables.
* Deploy the model as a web application for real-time forecasting.

---

## Author

Machine Learning Internship Project

Sales & Demand Forecasting Using Machine Learning
