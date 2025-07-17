# 💻 Laptop Price Predictor

Predict laptop prices using machine learning — a complete project from **exploratory data analysis** to **model deployment-ready code**.  
Created as part of the IE0005 Mini Project, this notebook demonstrates my **practical skills in data preprocessing, feature engineering, regression modeling, and evaluation**, with visual EDA built in Tableau.

## 🚀 Project Overview

In today's dynamic tech market, laptop pricing varies widely based on specifications like processor, RAM, storage, GPU, and brand.  
This project aims to build a machine learning model that can **accurately predict the price of a laptop** based on its hardware and configuration.

✅ **Goal**: Help consumers, retailers, or e-commerce platforms estimate fair prices for laptops using interpretable ML models.

## 📊 Exploratory Data Analysis (EDA)

Conducted an in-depth EDA using **Tableau** to understand price distribution and feature relationships.

🔗 [View the Interactive Tableau Dashboard](https://public.tableau.com/views/IE0005LaptopPriceEDA/Pricedistribution?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

**Highlights**:
- Correlation between RAM, storage type, brand, and price.
- Distribution of laptop types and processors.
- Insights on SSD vs. HDD impact on pricing.

## 🧠 Machine Learning Workflow

The Jupyter notebook contains the complete workflow:

- 📥 **Data Collection**: CSV dataset with laptop features and price.
- 🧼 **Data Cleaning & Preprocessing**:
  - Handled missing values.
  - Encoded categorical variables (Label Encoding, One-Hot).
  - Feature engineering: extraction of numeric values from strings (e.g., "8GB" → 8).
- 📈 **Model Training**:
  - Tried multiple regression models: Linear Regression, Ridge, Lasso, Decision Tree, Random Forest, and XGBoost.
  - Evaluated using **R² score**, **MAE**, **RMSE**.
- 🏆 **Best Model**:
  - Achieved high performance with **XGBoost Regressor**.

## 📁 Project Structure

```bash
├── [EL09]_IE0005_Mini_Project.ipynb   # Main notebook
├── requirements.txt                   # (Optional) dependencies
└── README.md                          # Project documentation
```

## 🔧 Tools & Technologies

- **Python**, **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**, **Scikit-learn**
- **XGBoost**
- **Tableau** (for EDA)
- **Jupyter Notebook**

## 📌 Key Learnings

- Hands-on application of **regression algorithms** for real-world pricing problems.
- Gained experience in **feature engineering**, model evaluation, and visualization.
- Demonstrated ability to **combine storytelling with data science** through Tableau dashboards.

## 🎯 Why This Matters

This project reflects my ability to:
- Handle end-to-end ML pipelines.
- Communicate findings through interactive visualizations.
- Work with real-world data and derive business value.

## 🙌 Credits

This project was developed as part of the IE0005 Mini Project by our project group.

Special thanks to all group members for their collaboration and contributions throughout the project.
