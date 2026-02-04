# Spare Part Inventory Forecasting

This project focuses on forecasting spare part demand using historical inventory and sales data. The goal is to help businesses optimize inventory levels, reduce stockouts, and minimize excess holding costs by leveraging data analysis and machine learning techniques.

## 📁 Project Structure

```
Forcasting-inventory/
│
│   ├── Forecasting.ipynb        # Jupyter Notebook for data analysis & forecasting
│   ├── spare_part_inventory.csv # Dataset used for the project
│   ├── catboost_info            # details catboost
│   └── README.md                # Project documentation
```

## 📊 Dataset

**File:** `spare_part_inventory.csv`

The dataset contains historical records related to spare parts inventory. Typical columns may include:

* Part ID / Part Name
* Date / Time
* Quantity Sold or Used
* Stock Levels
* Other relevant operational features

> Note: Ensure the dataset is clean (no missing or inconsistent values) before running the notebook.

## 🧠 Approach

1. **Data Cleaning & Preprocessing**

   * Handle missing values
   * Convert date columns to datetime format
   * Feature engineering if required

2. **Exploratory Data Analysis (EDA)**

   * Trend and seasonality analysis
   * Demand distribution

3. **Modeling & Forecasting**

   * Time series or machine learning models
   * Train-test split
   * Performance evaluation

4. **Results & Insights**

   * Forecasted demand
   * Business insights for inventory planning

## 🚀 Business Impact
* The final model outputs a JIT Reorder Flag. This flag is triggered based on:

* The predicted probability of a stockout within a specific timeframe.

* Current inventory levels and demand trends.

* This framework helps businesses reduce carrying costs and minimize service delays due to unavailable parts.

## 🛠️ Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook


