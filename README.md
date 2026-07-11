## 📌 Project Overview

This project develops a Machine Learning model to forecast Walmart's weekly sales using historical sales records, store information, promotional markdowns, and economic indicators.

The project follows a complete end-to-end Machine Learning workflow including:

- Data Understanding
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Feature Engineering
- Model Building
- Model Evaluation
- Model Comparison
- Model Saving for Future Deployment

The objective is to build a reliable sales forecasting model that can help retailers improve inventory planning, staffing, promotional strategies, and overall business decision-making.

---

# 🎯 Business Problem

Retail businesses depend heavily on accurate sales forecasts.

Poor forecasting can lead to:

- Overstocking inventory
- Product stockouts
- Increased storage costs
- Poor workforce planning
- Revenue loss
- Inefficient promotional campaigns

This project aims to predict weekly sales accurately using Machine Learning techniques.

---

# 📂 Dataset

The project uses Walmart historical sales data containing information about stores, departments, promotions, holidays, and economic conditions.

### Features Used

| Feature | Description |
|----------|-------------|
| Store | Store ID |
| Dept | Department ID |
| Date | Weekly Date |
| Weekly_Sales | Target Variable |
| IsHoliday | Holiday Indicator |
| Temperature | Weekly Temperature |
| Fuel_Price | Fuel Price |
| CPI | Consumer Price Index |
| Unemployment | Unemployment Rate |
| MarkDown1-5 | Promotional Discounts |
| Type | Store Type |
| Size | Store Size |

---

# 📁 Project Structure

```
Walmart-Weekly-Sales-Forecasting/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── models/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_datacleaning.ipynb
│   ├── 04_featureengineering.ipynb
│   └── 05_modelbuilding.ipynb
│
├── output/
│
├── src/
│
├── README.md
└── .gitignore

# 🔄 Machine Learning Workflow

The project follows the complete Machine Learning lifecycle:

1. Data Collection
2. Data Understanding
3. Exploratory Data Analysis (EDA)
4. Data Cleaning
5. Feature Engineering
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Model Comparison
10. Model Saving

---

# 📊 Exploratory Data Analysis

The dataset was explored to understand:

- Missing values
- Feature distributions
- Sales trends
- Correlation between variables
- Holiday sales patterns
- Store-wise performance
- Department-wise sales

Several visualizations were created to better understand the data before model building.

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values
- Converted date column to datetime format
- Checked data types
- Prepared clean dataset for feature engineering

---

# ⚙️ Feature Engineering

Additional features were created to improve model performance.

Examples include:

- Year
- Month
- Week
- Quarter
- Date-based features

Categorical variables were encoded where necessary before training the models.

---

# 🤖 Machine Learning Models

The following regression models were trained and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

Each model was evaluated using multiple regression metrics.

---

# 📈 Model Evaluation Metrics

Performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The models were compared to identify the best-performing algorithm for sales prediction.

---

# 🏆 Best Performing Model

After comparing all models, **Random Forest Regressor** achieved the best overall performance and produced the most accurate weekly sales predictions.

The trained model was saved using **Joblib** for future deployment and inference.

---

# 💻 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Joblib
- Jupyter Notebook
- VS Code
- Git
- GitHub

**Gaurav Dalakoti**
Machine Learning | Data Analytics | Supply Chain Analytics

GitHub: https://github.com/erdalakoti121
