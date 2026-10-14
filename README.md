# insurance-policy-risk-k-means-clustering
Unsupervised K-Means clustering model for insurance policyholders to analyse customer risk profiles, demographics, and coverage metrics for personalized underwriting.

# Insurance Policyholder Risk & Demographics Clustering

## 1. Business Problem
* **1.1. Business Objective:** Categorize insurance policyholders into distinct risk profiles to optimize policy pricing, risk assessment, and personalized coverage offerings.
* **1.2. Constraints:** Handling mixed categorical policy attributes and numerical financial metrics safely without introducing bias.

## 2. Data Dictionary
| Feature | Data Type | Description |
| :--- | :--- | :--- |
| `Policy` / Customer Attributes | Mixed | Demographics, age, income bracket, coverage levels, and past claims history. |

## 3. Exploratory Data Analysis (EDA)
* **3.1. Summary:** Generated statistical summaries of customer risk metrics and claim frequencies.
* **3.2. Univariate Analysis:** Analyzed age spread, income distributions, and payout amounts.
* **3.3. Bivariate Analysis:** Examined correlations between premium amounts and customer claim histories.

## 4. Data Pre-processing
* **4.1. Data Cleaning & Feature Engineering:** Handled null values, performed one-hot encoding on categorical attributes, and scaled numerical columns.

## 5. Model Building
* **5.1. Model Execution:** Trained K-Means models across preprocessed policy datasets.
* **5.2. Scree Plot:** Plotted within-cluster sum of squares (WCSS) to find the optimal $k$ value.
* **5.3. Validation & Insights:** Evaluated clustering configurations, assigned risk tiers, and interpreted underwriting insights.

## 6. Business Benefits & Impact
* Empowers underwriters to price premiums more accurately, mitigate portfolio risk, and target low-risk customers with competitive discounts.
