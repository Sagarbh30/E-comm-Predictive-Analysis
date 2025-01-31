E-commerce Sales Analysis and Prediction :


Project Overview

This project focuses on analyzing an e-commerce dataset to gain insights into product sales, customer preferences, and ratings. Additionally, it implements a machine learning model to predict product sales based on various features.

Dataset Information

The dataset consists of 2000 records and includes the following columns:

Product_ID: Unique identifier for each product.

Category: Category of the product (e.g., Electronics, Clothing, Home, etc.).

Price: Price of the product.

Quantity_Sold: Number of units sold.

Ratings: Average customer rating of the product.

Objectives

Data Analysis: Explore the dataset and summarize key statistics.

Data Visualization: Generate visual insights into product sales and ratings.

Product Performance Analysis:

Identify the highest-selling product.

Identify the highest-rated product.

Determine the most in-demand product category.

Machine Learning Model:

Train a Linear Regression model to predict product sales.

Evaluate the model’s performance.

Visualize residuals to analyze prediction errors.

Data Analysis

The script provides:

Basic descriptive statistics of the dataset.

Identification of missing values.

Distribution of product categories.

Data Visualization

The project includes various visualizations:

Pair Plot: Shows relationships between numerical variables grouped by category.

Total Quantity Sold by Category: Bar plot displaying total sales per category.

Product Sales & Ratings:

Bar plots showcasing sales and ratings of each product.

Helps identify top-performing and least-performing products.

Most Demanding Product Category: Bar plot visualizing the most popular product category based on total sales.

Machine Learning Model

A Linear Regression Model is used to predict the Quantity_Sold based on other numerical features.

Steps Involved:

Data Preprocessing:

Dropping irrelevant columns (Product_ID, Category).

Splitting the data into training and testing sets.

Model Training:

A linear regression model is trained on the dataset.

Predictions & Evaluation:

The model predicts Quantity_Sold for the test set.

Evaluation metrics:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R-squared Score (R²)

Residual Analysis:

A histogram of residuals is plotted to evaluate the model's accuracy.

Results & Insights

The highest-selling product and highest-rated product were identified.

Most demanding category was determined based on total sales.

Linear regression provided a baseline model for predicting product sales.

The model’s performance was analyzed using evaluation metrics.

Future Enhancements

Implement additional models such as Random Forest or XGBoost for better accuracy.

Include more features like customer reviews, seasonal trends, and promotions.

Optimize the dataset by adding external market trend data.

Repository Structure

📂 ecomm_sales_analysis
├── ecomm_data_2000.csv      # Dataset
├── ecomm_analysis.py        # Main Python script
├── README.md                # Project documentation
├── images/                  # Folder for generated plots
└── models/                  # Folder to save trained models (optional)

How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/ecomm_sales_analysis.git
cd ecomm_sales_analysis

Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

Run the script:

python ecomm_analysis.py

Conclusion

This project provides valuable insights into e-commerce sales and demonstrates a practical application of data analysis and machine learning. Future work can improve model accuracy and incorporate additional business intelligence techniques.

