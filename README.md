# Retail Sales Data Analysis Project

## Overview
A comprehensive data analysis project demonstrating advanced Python analytics capabilities through the analysis of an online retail dataset. This project showcases end-to-end data science workflows, from data cleaning and exploration to advanced customer segmentation using machine learning techniques. The analysis was primarily conducted as a single-pass exploration, with subsequent modifications focused mainly on visualization enhancement and documentation clarity rather than analytical iterations.

## Dataset Source
The analysis uses the "Online Retail" dataset from the UCI Machine Learning Repository:
- Source: [UCI Machine Learning Repository - Online Retail Dataset](https://archive.ics.uci.edu/dataset/352/online+retail)
- Time Period: December 2010 to December 2011
- Business Context: UK-based non-store online retail specializing in unique all-occasion gifts
- Customer Base: Mix of retail and wholesale customers
- Transaction Types: All transactions including sales, returns, and cancellations

Dataset Characteristics:
- Transactional data spanning one year
- Contains complete purchase history
- Includes customer details and product information
- Features both retail and wholesale pricing
- International customer base with focus on UK market

## Key Project Components

### 1. Data Cleaning & Validation
- Systematic data quality assessment and cleaning
  - Identification and handling of anomalous data (cancelled orders, negative quantity/prices, non-standard stock codes)
  - Validation of high-value transactions
  - Duplicate transaction analysis
- Advanced data quality checks
  - Statistical outlier detection
  - Transaction pattern validation
  - Price and quantity range validation
- Data standardization and transformation
  - DateTime conversions and standardization
  - Customer ID formatting
  - Stock code standardization
  - Derived metric calculations

### 2. Business Analysis & Visualization
- Sales pattern analysis
  - Temporal trends visualization
  - Geographic distribution mapping
  - Product category performance
  - Customer purchase behaviors
- Interactive visualizations
  - Time series trend plots
  - Choropleth maps for geographical analysis
  - Distribution analysis plots
  - Transaction pattern visualization
- Business metric development
  - Customer value calculations
  - Product performance metrics
  - Sales trend analysis
  - Market penetration insights

### 3. Product Analysis & Categorization
- Hierarchical clustering implementation
  - Product grouping based on characteristics
  - Price-based categorization
  - Stock code pattern analysis
  - Category performance evaluation
- Product insights
  - Category-based sales analysis
  - Product association patterns
  - Inventory optimization insights

### 4. Customer Segmentation & Statistical Analysis
- Advanced statistical analysis
  - Distribution testing
  - Outlier analysis
  - Likelihood ratio testing
  - Normality validation
- Machine learning implementation
  - Gaussian Mixture Models for segmentation
  - Hyperparameter optimization with Optuna
  - Feature engineering
  - Model evaluation metrics
- Customer behavior modeling
  - Purchase pattern identification
  - Value-based categorization
  - Segment-based insights
  - Customer lifecycle analysis

## Key Insights Generated
- Identified key customer segments and their characteristics
- Discovered product category performance patterns
- Mapped geographical sales distribution
- Analyzed temporal sales trends
- Generated actionable business recommendations

## Technical Implementation

### Tools & Libraries
- Data Processing: pandas, numpy
- Machine Learning: scikit-learn, scipy
- Visualization: plotly
- Statistical Analysis: statsmodels
- Optimization: Optuna

### Project Structure
```
├── notebooks/
│   ├── 1. data cleaning and exploration.ipynb # Data cleaning & exploration
│   ├── 2. data analysis and visualization.ipynb # Business analysis & visualization
│   ├── 3. machine learning - stock clustering.ipynb        # Product categorization and stock analysis
│   └── 4. machine learning - customer segmentation through clustering.ipynb  # Statistical analysis & segmentation
```

## Contact
[Lance Baldridge]
- LinkedIn: [Your LinkedIn]
- Email: [Your Email]

This project demonstrates proficiency in:
- Data Analysis & Statistics
- Machine Learning
- Python Programming
- Business Analytics
- Data Visualization