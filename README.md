### Global E‑Commerce Sales Analysis and Profit Prediction

This project analyzes a global e‑commerce dataset to understand sales patterns across regions, customer segments, and product categories, and builds machine learning models to predict order‑level profit.
It includes seven research questions, each implemented in its own Jupyter notebook, producing publication‑ready figures (PDF) and tables (CSV).

📦 Dataset Information
Dataset Name: Global E‑Commerce Sales Data Analysis

Source: Kaggle: https://www.kaggle.com/datasets/bibirehana/global-e-commarce-sales-data-analysis
Format: Excel (.xlsx)
Rows: 2000
Columns: 15

Target Variable: Profit

Task Type: Regression

Key fields include:
Order_ID, Order_Date, Customer_Segment, Region, Product_Category, Quantity, Unit_Price, Discount_Percent, Total_Sales, Shipping_Cost, Profit, etc.

project/
|
code/
│
├── RQ1.ipynb
├── RQ2.ipynb
├── RQ3.ipynb
├── RQ4.ipynb
├── RQ5.ipynb
├── RQ6.ipynb
├── RQ7.ipynb
|
charts/
├── rq1_outputs/
├── rq2_outputs/
├── rq3_outputs/
├── rq4_outputs/
├── rq5_outputs/
├── rq6_outputs/
├── rq7_outputs/
│
└── README.md

Each notebook:
Loads the raw dataset
Performs preprocessing
Answers one research question
Generates tables (CSV)
Generates figures (PDF)
Saves outputs in its respective folder

🔍 Research Questions
1 How do total sales and profit vary across regions and months?

2 Which product categories and products contribute most to revenue and profit?

3 How do customer segments differ in average order value and profitability across regions?

4 What is the relationship between discount percent and profit margin across product categories?

5 How do shipping costs vary by region and product category, and how do they affect profit?

6 How do payment method preferences differ across regions, and how are they associated with order value?

7 To what extent can profit be predicted using machine learning models?

🧠 Methodology Overview
1. Data Preprocessing
Convert dates
Handle missing values
Create derived fields (e.g., Year‑Month, Profit Margin)
Encode categorical variables

2. Exploratory Data Analysis
Grouped Summaries
Trend analysis
Category‑wise comparisons
Visualizations for each RQ

3. Machine Learning (RQ7)
Train/test split
One‑hot encoding for categorical variables

Models used:
Linear Regression
Random Forest Regressor

Evaluation metrics:
MAE
RMSE
R² Score

4. Output Generation
All tables saved as CSV
All figures saved as PDF
Each notebook is self‑contained and reproducible

▶️ How to Run the Code (Kaggle Instructions)
Upload the dataset to your Kaggle notebook environment

Place the Excel file under:
/kaggle/input/global-ecommerce-sales/

Upload all seven .ipynb notebooks into your Kaggle project.

Open any notebook (e.g., RQ1.ipynb).

Run all cells:

The notebook will:
Load the dataset
Process data
Generate tables (CSV)
Generate figures (PDF)
Save outputs in a folder like rq1_outputs/
Download outputs from the Kaggle file browser if needed.
Each notebook is independent—run them in any order.

📊 Expected Outputs

Each RQ produces:
Figures (PDF)
Line charts
Bar charts
Scatter plots
Boxplots
Feature importance plots

Tables (CSV)
Monthly sales summaries
Category and product rankings
Segment‑wise AOV tables
Discount vs margin summaries
Shipping cost comparisons
Payment method distributions
ML model performance metrics

📄 License This project is for academic and educational use.
