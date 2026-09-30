# BigBasket Product & Price Analytics

A data analytics and machine learning case study on BigBasket product data, focusing on product trends, pricing, discounts, ratings, and sale-price prediction.

## Project Overview

This project analyzes the BigBasket product dataset to understand product-level patterns across categories, sub-categories, brands, and product types. The analysis includes data cleaning, exploratory data analysis, pricing and discount analysis, correlation analysis, and machine learning-based price prediction.

## Dataset

The dataset contains **27,555 product records** with information such as:

- Product name
- Category
- Sub-category
- Brand
- Sale price
- Market price
- Product type
- Rating
- Product description

### Dataset Statistics

- **27,555** products
- **11** categories
- **90** sub-categories
- **2,313** brands
- **426** product types
- **23,540** unique products

## Objectives

- Explore the distribution of BigBasket products across different categories and brands.
- Analyze sale price and market price relationships.
- Identify discount and pricing patterns.
- Study product ratings and their distribution.
- Perform exploratory data analysis and visualization.
- Build machine learning models for sale-price prediction.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- XGBoost
- Jupyter Notebook / Google Colab

## Data Analysis

The project includes:

### 1. Data Cleaning

- Inspected dataset structure and data types.
- Handled missing values.
- Processed product ratings.
- Prepared numerical and categorical features for analysis and modeling.

### 2. Exploratory Data Analysis

Analyzed:

- Category-wise product distribution
- Sub-category distribution
- Brand distribution
- Product ratings
- Sale prices
- Market prices
- Discount patterns
- Relationships between numerical variables

The dataset contains products across **11 categories and 90 sub-categories**, providing a broad view of BigBasket's product catalog.

### 3. Pricing Analysis

The project compares:

- `sale_price`
- `market_price`

to understand pricing and discount patterns across products and categories.

### 4. Rating Analysis

The average product rating in the dataset is approximately **3.94**, while the median rating is **4.1**.

Missing ratings were handled using the mean rating.

## Machine Learning

The project explores machine learning models for predicting product sale prices.

### Models Used

- Linear Regression
- XGBoost

### XGBoost Performance

The XGBoost model achieved:

- **R² Score: 98.18%**
- **MAE: ₹9.46**

These results indicate a strong predictive fit on the evaluated test data.

## Project Workflow

```text
Raw BigBasket Dataset
        ↓
Data Loading
        ↓
Data Cleaning & Missing Value Treatment
        ↓
Exploratory Data Analysis
        ↓
Pricing & Discount Analysis
        ↓
Feature Engineering
        ↓
Train/Test Split
        ↓
Machine Learning Models
        ↓
Model Evaluation
        ↓
Insights & Conclusions
