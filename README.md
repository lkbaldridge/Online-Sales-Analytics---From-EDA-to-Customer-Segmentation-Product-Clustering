# Customer Segmentation & Business Insights for Online Retail

This repository contains a comprehensive, end-to-end data science project that analyzes a transactional dataset to derive actionable business intelligence. The project progresses from foundational data cleaning and exploratory analysis to advanced unsupervised machine learning for product categorization and customer segmentation.

The culmination of this work is a **formal academic-style research paper** that details the methodology and findings of the machine learning pipeline.

[Read the Full Research Paper Here](https://github.com/lkbaldridge/Online-Sales-Analytics---From-EDA-to-Customer-Segmentation-Product-Clustering/blob/main/Academic%20Paper.pdf)

---

### Project Summary & Key Achievements

This project successfully answers critical business questions by transforming raw data into strategic insights.

-   **Business Insights:** Identified strong Q4 seasonality, confirmed the Pareto Principle (over 28% of revenue comes from ~1% of customers), and mapped the company's core markets in the UK and Western Europe.
-   **Automated Product Categorization:** Developed a novel hybrid model combining **Hierarchical Clustering and NLP** to automatically categorize thousands of unique products, solving a key business problem and enabling deeper analysis.
-   **Data-Driven Customer Personas:** Implemented a **Gaussian Mixture Model (GMM)**, optimized with Optuna, to segment the customer base into five distinct, actionable personas, including:
    -   **Core Active:** The loyal, high-frequency customer base.
    -   **High-Value VIPs:** High-spending accounts critical to revenue.
    -   **At-Risk:** Customers showing signs of lapsing, representing a key target for re-engagement.

---

### Project Structure & Notebooks

This analysis is broken down into four sequential Jupyter notebooks that tell the complete story of the project, from raw data to final insights.

-   **`01_Data_Cleaning_and_EDA.ipynb`**
    -   *Focus:* Foundational data cleaning, handling of over 100,000 null values, filtering cancelled orders, and investigating data quality anomalies.
-   **`02_Business_Insights_and_Visualization.ipynb`**
    -   *Focus:* High-level business analysis, including visualization of temporal trends, geographic sales distribution, and identification of top customers.
-   **`03_Product_Clustering_with_Hierarchical_NLP.ipynb`**
    -   *Focus:* The first ML phase. Implements a hybrid model to automatically categorize all products, enriching the dataset for the final analysis.
-   **`04_Customer_Segmentation_with_GMM.ipynb`**
    -   *Focus:* The final ML phase. Involves RFM-style feature engineering, statistical validation, hyperparameter tuning with Optuna, and GMM implementation to define customer personas.

---

### Technical Implementation

-   **Data Processing & Analysis:** Pandas, NumPy
-   **Machine Learning:** Scikit-learn, SciPy
-   **Statistical Analysis:** Statsmodels, Pingouin
-   **Visualization:** Plotly
-   **Hyperparameter Optimization:** Optuna
-   **NLP:** NLTK

---

### Dataset Source

The analysis uses the "Online Retail" dataset from the UCI Machine Learning Repository.
-   **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail)
-   **Context:** UK-based online retailer specializing in unique gifts.
-   **Data:** Contains all transactions from December 2010 to December 2011.

---

### Contact
Lance Kendrick F. Baldridge
- **LinkedIn:** [linkedin.com/in/lance-baldridge-2a291097](https://www.linkedin.com/in/lance-baldridge-2a291097/)
- **Email:** lance_baldridge@outlook.com
