<div align="center">

# Sales Data Exploratory Analysis with Python

### Retail customer and product analysis using Python, Pandas, Matplotlib, and Seaborn

[![Python](https://img.shields.io/badge/Python-EDA-3776AB?logo=python&logoColor=white)](Sales_Data_EDA_Python.ipynb)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)](Sales_Data_EDA_Python.ipynb)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-Data%20Processing-013243?logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)](https://seaborn.pydata.org/)

</div>

---

## Table of Contents

- [Project Overview](#project-overview)
- [Business Objective](#business-objective)
- [Project Highlights](#project-highlights)
- [Tools and Technologies](#tools-and-technologies)
- [Dataset Overview](#dataset-overview)
- [Analysis Workflow](#analysis-workflow)
- [Business Questions](#business-questions)
- [Key Visualizations](#key-visualizations)
- [Key Insights](#key-insights)
- [Business Recommendations](#business-recommendations)
- [Repository Structure](#repository-structure)
- [How to Run the Project](#how-to-run-the-project)
- [Skills Demonstrated](#skills-demonstrated)
- [Project Outcome](#project-outcome)
- [Author](#author)

---

## Project Overview

This project performs exploratory data analysis on a retail sales dataset using Python. It converts transaction-level data into practical insights about customer purchasing behavior, demographic segments, geographic performance, product categories, professions, and best-selling products.

The complete analysis is documented in [`Sales_Data_EDA_Python.ipynb`](Sales_Data_EDA_Python.ipynb), from data-quality checks and cleaning through aggregation, visualization, insight generation, and business recommendations.

> **Business goal:** identify the customers, regions, and products that contribute most to sales so marketing and inventory decisions can be better targeted.

---

## Business Objective

The analysis is designed to:

- Understand customer purchasing behavior
- Identify high-value demographic segments
- Compare sales performance across states
- Evaluate product-category contribution
- Analyze profession-based purchasing patterns
- Identify products with the highest order quantities
- Translate analysis results into business recommendations

---

## Project Highlights

- End-to-end exploratory analysis in a reproducible Jupyter Notebook
- Data cleaning, null handling, duplicate checks, and type validation
- Customer analysis by gender, age group, state, and profession
- Product analysis by category and order quantity
- Aggregation and ranking with Pandas
- Business-focused visual storytelling with Matplotlib and Seaborn
- Actionable recommendations derived from observed purchasing patterns

---

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Core analysis and data-processing language |
| Jupyter Notebook | Interactive and reproducible analytical workflow |
| Pandas | Cleaning, transformation, grouping, and aggregation |
| NumPy | Numerical data operations |
| Matplotlib | Chart creation and customization |
| Seaborn | Statistical and categorical visualizations |
| GitHub | Version control and portfolio documentation |

---

## Dataset Overview

The source file is available as [`Sales_Data.csv`](Sales_Data.csv).

The retail transaction dataset includes customer and purchase attributes such as:

| Area | Example Fields |
|---|---|
| Customer profile | Gender and age group |
| Geography | State |
| Occupation | Profession |
| Product | Product category and product identifier |
| Transaction | Quantity ordered and sales amount |

These fields enable segmentation of revenue and order activity across customer, geographic, and product dimensions.

---

## Analysis Workflow

### 1. Data Understanding

- Loaded the CSV dataset with Pandas
- Reviewed rows, columns, data types, and summary statistics
- Identified the fields relevant to business analysis

### 2. Data Cleaning

- Removed unnecessary columns
- Checked and handled missing values
- Checked for duplicate records
- Validated and converted data types where required
- Prepared a clean analytical dataset

### 3. Exploratory Data Analysis

- Grouped customers and sales by demographic attributes
- Ranked states and product categories by performance
- Compared transaction volume with sales contribution
- Evaluated profession-wise purchasing patterns
- Identified high-quantity products

### 4. Visualization and Interpretation

- Created business-focused charts
- Interpreted the strongest segments and categories
- Converted findings into practical recommendations

---

## Business Questions

The notebook answers the following questions:

1. Which gender contributes the highest transaction volume and sales?
2. Which age groups generate the most revenue?
3. Which states contribute the highest sales and order quantities?
4. Which product categories perform best by transactions and sales amount?
5. How do purchasing patterns vary across gender and product category?
6. Which professions contribute the most transactions and revenue?
7. Which products record the highest order quantities?

---

## Key Visualizations

### Sales by Gender

<p align="center">
  <img src="Images/Gender%20wise%20Total%20Sales%20Amount.png" alt="Total retail sales amount by customer gender" width="760">
</p>

### Sales by Age Group

<p align="center">
  <img src="Images/Age%20Group%20Wise%20Total%20Amount.png" alt="Total retail sales amount by customer age group" width="760">
</p>

### Top Five States by Sales

<p align="center">
  <img src="Images/Top%205%20States%20by%20Total%20Sales%20Amount.png" alt="Top five states ranked by total retail sales amount" width="760">
</p>

### Product Category Performance

<p align="center">
  <img src="Images/Product%20Category%20Wise%20Total%20Amount.png" alt="Total retail sales amount by product category" width="760">
</p>

### Sales by Profession

<p align="center">
  <img src="Images/Profession%20Wise%20Total%20Amount.png" alt="Total retail sales amount by customer profession" width="760">
</p>

---

## Key Insights

- **Female customers lead sales:** they contribute more revenue than male customers.
- **The 26–35 age group is the strongest segment:** it generates the highest sales and transaction volume.
- **Uttar Pradesh, Maharashtra, and Karnataka are top markets:** these states rank among the strongest contributors to sales.
- **Beauty, Sports, and Electronics perform strongly:** these categories account for a significant share of revenue.
- **IT, Healthcare, and Aviation are valuable profession segments:** customers in these groups generate strong sales.
- **Several products consistently achieve high order quantities:** these products represent potential best sellers and inventory priorities.

---

## Business Recommendations

1. Prioritize campaigns aimed at female customers while testing tailored messaging for other segments.
2. Develop targeted promotions for the high-performing 26–35 age group.
3. Strengthen inventory availability and marketing activity in top-performing states.
4. Give high-performing product categories greater visibility in promotions and merchandising.
5. Test profession-based campaigns for customers working in IT, Healthcare, and Aviation.
6. Monitor best-selling products closely to reduce stockout risk and protect revenue.

---

## Repository Structure

```text
Sales-Data-EDA-Python/
├── Images/
│   ├── Age Group Wise Total Amount.png
│   ├── Gender wise Total Sales Amount.png
│   ├── Product Category Wise Total Amount.png
│   ├── Profession Wise Total Amount.png
│   └── Top 5 States by Total Sales Amount.png
├── Sales_Data.csv
├── Sales_Data_EDA_Python.ipynb
└── README.md
```

### Quick Links

- [Open the analysis notebook](Sales_Data_EDA_Python.ipynb)
- [View the source dataset](Sales_Data.csv)
- [Browse all visualizations](Images/)

---

## How to Run the Project

### Prerequisites

- Python 3.9 or newer
- Jupyter Notebook or JupyterLab
- Pandas
- NumPy
- Matplotlib
- Seaborn

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Chanchadiyakaushal201/Sales-Data-EDA-Python.git
   cd Sales-Data-EDA-Python
   ```

2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```

3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `Sales_Data_EDA_Python.ipynb`.

5. Confirm that `Sales_Data.csv` is available in the repository root, then run the notebook cells in order.

---

## Skills Demonstrated

- Python programming
- Data cleaning and preparation
- Exploratory data analysis
- Missing-value handling
- Duplicate detection
- Data-type validation
- Pandas grouping and aggregation
- Customer segmentation
- Product and geographic analysis
- Matplotlib and Seaborn visualization
- Business insight generation
- Analytical storytelling
- Portfolio documentation

---

## Project Outcome

This project demonstrates how Python can be used to clean, explore, visualize, and interpret retail sales data. The resulting analysis identifies valuable customer groups, strong markets, high-performing categories, and best-selling products that can inform marketing and inventory decisions.

---

## Author

### Kaushal Chanchadiya

Aspiring Data Analyst focused on converting raw data into clear business insights through analytics, visualization, and data storytelling.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kaushal%20Chanchadiya-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kaushalchanchadiya162004/)
[![GitHub](https://img.shields.io/badge/GitHub-Chanchadiyakaushal201-181717?logo=github&logoColor=white)](https://github.com/Chanchadiyakaushal201)

---

<div align="center">

If this project helped you, consider giving the repository a ⭐.

[Back to top](#sales-data-exploratory-analysis-with-python)

</div>
