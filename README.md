# Customer Shopping Behavior Analysis

## Overview

This project focuses on analyzing customer shopping behavior using Python, PostgreSQL, SQL, and Power BI. The objective is to identify customer purchasing patterns, understand spending behavior, analyze customer segments, and generate actionable business insights.

The project follows an end-to-end data analytics workflow, starting with data loading and cleaning in Python, followed by exploratory data analysis, SQL-based business analysis, and interactive dashboard development in Power BI.

## Dataset

- **Total Records:** 3,900
- **Total Columns:** 18
- **Missing Values:** 37 values in the Review Rating column.

### Key Features
- Customer demographics (Age, Gender, Location)
- Purchase information (Item, Category, Purchase Amount)
- Shopping behavior (Discounts, Previous Purchases, Purchase Frequency)
- Subscription status and review ratings
- Shipping type and seasonal preferences

## Tools & Technologies

- **Python:** Data loading, cleaning, and exploratory data analysis.
- **Pandas:** Data manipulation and preprocessing.
- **PostgreSQL:** Database management and SQL-based analysis.
- **SQL:** Business queries and customer segmentation.
- **Power BI:** Interactive dashboard development.
- **Gamma:** Presentation creation.
- **Jupyter Notebook:** Python analysis environment.

## Project Workflow

### 1. Data Loading & Exploration
- Imported the dataset using Pandas.
- Examined dataset structure and data types.
- Generated descriptive statistics.
- Identified missing values and potential inconsistencies.

### 2. Data Cleaning & Preparation
- Handled 37 missing Review Rating values using category-wise median imputation.
- Standardized column names using snake_case.
- Created an Age Group feature.
- Created a Purchase Frequency Days feature.
- Checked redundant columns and removed `promo_code_used`.

### 3. Exploratory Data Analysis (EDA)
- Explored customer demographics and purchasing patterns.
- Analyzed product categories and spending behavior.
- Examined discount usage and subscription trends.

### 4. SQL Business Analysis

Loaded the cleaned dataset into PostgreSQL and performed business analysis to answer questions such as:

1. Revenue comparison by gender.
2. High-spending customers using discounts.
3. Top 5 products by average rating.
4. Standard vs. Express shipping comparison.
5. Subscribers vs. non-subscribers spending analysis.
6. Products most dependent on discounts.
7. Customer segmentation (New, Returning, Loyal).
8. Top 3 products in each category.
9. Relationship between repeat purchases and subscriptions.
10. Revenue contribution by age group.

### 5. Power BI Dashboard
Developed an interactive dashboard to visualize customer shopping behavior and present key business metrics and insights.

### 6. Reporting & Presentation
- Created a project report documenting the analysis and findings.
- Prepared a presentation using Gamma to communicate the project's objectives, methodology, and business insights.

## Dashboard

The Power BI dashboard provides a visual overview of customer shopping behavior, revenue distribution, purchasing patterns, and customer segments.



## Key Business Recommendations

- Encourage subscriptions through exclusive customer benefits.
- Introduce loyalty programs to retain repeat customers.
- Review discount strategies to balance sales and profitability.
- Promote highly rated and popular products.
- Use customer demographics and purchasing behavior for targeted marketing.

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── reports/
├── presentation/
└── README.md
```

## How to Run

1. Clone this repository:

   ```bash
   https://github.com/tanayhrs276-netizen/Customer_behaviour_Analysis_report.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Customer-Shopping-Behavior-Analysis
   ```

3. Install the required Python libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
   ```

4. Open the Jupyter Notebook and execute the data loading, cleaning, and EDA steps.

5. Set up PostgreSQL and import the cleaned dataset.

6. Execute the SQL queries available in the `sql/` directory.

7. Open the Power BI `.pbix` file to explore the interactive dashboard.

8. Review the final project report and Gamma presentation.

## License

This project is licensed under the MIT License.

---

**Author:** Tanay Harsh

**Project:** Customer Shopping Behavior Analysis
