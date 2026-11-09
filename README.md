# Customer Shopping Behavior Analysis

## Overview

This project focuses on analyzing customer shopping behavior to identify purchasing patterns, customer preferences, and factors influencing buying decisions.

The objective is to transform raw retail data into meaningful business insights that can help improve customer engagement, increase sales, strengthen customer loyalty, and optimize marketing strategies.

The project follows an end-to-end data analytics workflow, starting from data preparation and exploratory analysis in Python to SQL-based business analysis and interactive dashboard development using Power BI.

## Business Problem

A leading retail company wants to better understand its customers' shopping behavior to improve sales, customer satisfaction, and long-term loyalty.

This project aims to answer questions related to:

- Customer purchasing patterns and preferences.
- Product category performance.
- Impact of discounts and customer reviews.
- Shopping behavior across customer demographics.
- Payment methods and purchase frequency.
- Customer segmentation and subscription status.
- Factors influencing customer purchasing decisions.

## Dataset

The project uses the **Customer Shopping Behavior Dataset** containing customer-level shopping information.

The dataset includes attributes such as:

- Customer ID
- Age and Gender
- Item Purchased
- Category
- Purchase Amount
- Location
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

**Dataset Format:** CSV

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data loading, cleaning and EDA |
| Pandas | Data manipulation and preprocessing |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Exploratory data visualization |
| PostgreSQL / MySQL / SQL Server | SQL-based business analysis |
| Power BI | Interactive dashboard development |
| Gamma | Presentation creation |
| GitHub | Project version control and hosting |

## Project Workflow

### 1. Data Loading and Exploration (Python)

- Imported the dataset using Pandas.
- Examined dataset structure and dimensions.
- Checked column names and data types.
- Identified missing values and duplicate records.
- Performed initial exploratory data analysis.

### 2. Data Cleaning and Preparation

- Handled missing values.
- Checked and removed duplicate records where necessary.
- Corrected data types.
- Standardized column names and categorical values.
- Prepared the dataset for further analysis.

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand:

- Customer demographics.
- Purchase amount distribution.
- Popular product categories.
- Seasonal purchasing trends.
- Customer review ratings.
- Payment method preferences.
- Discount and subscription patterns.

### 4. SQL Business Analysis

Loaded the cleaned dataset into a relational database and performed SQL analysis.

Queries focused on:

- Revenue analysis.
- Customer segmentation.
- Category-wise sales performance.
- Subscription-based customer analysis.
- Average purchase amount.
- Shipping preferences.
- Discount usage patterns.
- Customer purchasing frequency.

SQL techniques included:

- SELECT, WHERE and ORDER BY
- GROUP BY and HAVING
- Aggregate Functions
- CASE Statements
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions

### 5. Power BI Dashboard

Developed an interactive dashboard to present important business metrics and customer shopping insights.

Dashboard features include:

- Key Performance Indicators (KPIs).
- Customer purchase analysis.
- Revenue and category analysis.
- Customer segmentation.
- Interactive filters and slicers.
- Visual comparisons of shopping patterns.

### 6. Report and Presentation

Prepared project documentation and a presentation to communicate the analytical findings.

- **Project Report:** Business problem, methodology, analysis, findings and recommendations.
- **Presentation:** Created using Gamma to present the project workflow, key insights and business recommendations.

## Dashboard

The Power BI dashboard provides an interactive view of customer shopping behavior and business performance.

**Dashboard Preview:**

<!-- Add your Power BI dashboard screenshot here -->

![Dashboard Preview](Images/dashboard_preview.png)

**Live Dashboard:** [View Interactive Power BI Dashboard](YOUR_POWER_BI_PUBLIC_LINK)

## Key Results and Business Insights

The analysis aims to identify:

- High-performing product categories.
- Differences in customer purchasing behavior.
- Revenue contribution across customer segments.
- Relationships between discounts and purchasing patterns.
- Customer preferences regarding payment and shipping.
- Opportunities to improve customer retention and engagement.

**Note:** Actual findings and numerical results will be added after completing the analysis.

## Business Recommendations

Based on the analytical findings, the company can:

- Develop targeted marketing campaigns.
- Improve customer loyalty programs.
- Optimize discount strategies.
- Focus on high-performing product categories.
- Improve customer engagement.
- Use purchasing trends to support inventory planning.

## How to Run the Project

### Prerequisites

Install the following:

- Python 3.x
- Jupyter Notebook
- PostgreSQL / MySQL / SQL Server
- Power BI Desktop

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/Customer-Shopping-Behavior-Analysis.git
```

### Step 2: Navigate to the Project Directory

```bash
cd Customer-Shopping-Behavior-Analysis
```

### Step 3: Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Run Python Analysis

Open Jupyter Notebook:

```bash
jupyter notebook
```

Run the Python notebooks in sequence to perform data loading, cleaning and exploratory analysis.

### Step 5: Execute SQL Queries

- Create a database in PostgreSQL, MySQL or SQL Server.
- Import the cleaned dataset.
- Execute the SQL scripts available in the SQL folder.

### Step 6: Open Power BI Dashboard

Open the `.pbix` file using Power BI Desktop.

Update the data source if required and refresh the dashboard.

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Dataset/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── data_analysis.ipynb
│
├── SQL/
│   └── business_analysis.sql
│
├── PowerBI/
│   └── customer_shopping_behavior.pbix
│
├── Images/
│   └── dashboard_preview.png
│
├── Report/
│   └── project_report.pdf
│
├── Presentation/
│   └── project_presentation.pdf
│
└── README.md
```

## Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Python for Data Analytics
- SQL Querying and Business Analysis
- Data Visualization
- Power BI Dashboard Development
- Business Intelligence
- Data-Driven Decision Making
- Business Reporting and Presentation

## Author

**Your Name**

GitHub: [Your GitHub Profile](https://github.com/YOUR_USERNAME)

---

*This project is developed as part of an academic Data Analysis and Visualization project, demonstrating an end-to-end approach to solving real-world retail business problems using data analytics tools.*
