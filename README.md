# Sales Performance & Strategy Analysis


--- 

## Executive Summary

This project evaluates the effectiveness of three sales outreach strategies used to promote a newly launched office stationery product line.

Using a structured analytics workflow 

"""
### **Data Validation > Exploratory Data Analysis > Strategy Evaluation**
"""

the project identifies which approach drives the strongest revenue performance and provides data-backed recommendations.

The analysis finds that the **Email + Call strategy consistently outperforms single-channel outreach**, indicating that multi-touch engagement increases conversion and revenue generation.

---

## Business Context

The company recently introduced a new line of office stationery products designed to enhance creativity and brainstorming efficiency in professional environments.

To support adoption, the sales team implemented three outreach strategies:
- Email  
- Phone Call  
- Email + Call  

### Management wants to determine:

- Which strategy generates the highest revenue?
- Does combining communication channels improve results?
- How do customer tenure and engagement impact purchasing behavior?
- What strategic adjustments should be made moving forward?

---

## Project Objectives

- Validate dataset quality and structural integrity  
- Identify inconsistencies and anomalies  
- Explore revenue and behavioral patterns  
- Compare strategy performance using quantitative analysis  
- Deliver actionable business recommendations  

---

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## Project Structure

```text

#### sales-performance-strategy-analysis
├── data/              # Raw and processed data
│
├── Docs/              # Documentation, Instruction
│
├── notebooks/         # Jupyter notebooks with analysis
│   ├── 01_data_validation/   	# Exploratory Data Analysis
│   ├── 02_eda/ 		# Data Cleaning and Transformation
│   └── 03_analysis/  	# Data Analysis & Statistical Testing
│
├── README.md          # Project documentation
│
└── .gitignore         # Files/folders to exclude from Git

```
---

## Dataset Overview

- 15,000 customer records  
- 8 variables  
- 6-week post-launch observation window  
- One row per customer  

### Key Variables

| Variable | Description |
|----------|------------|
| sales_method | Outreach strategy used |
| customer_id | Unique customer identifier |
| nb_sold | Number of new products sold |
| revenue | Revenue generated |
| years_as_customer | Customer tenure |
| nb_site_visits | Website visits (last 6 months) |
| week | Weeks since product launch |
| state | Customer location |

---

## Data Validation  
**Notebook:** `01_data_validation.ipynb`

This phase focuses strictly on assessing data quality before performing analysis.

### Key Validation Checks:
- Structural consistency (one row per customer)
- Missing value assessment
- Categorical standardization
- Outlier detection
- Data type verification

### Findings:
- 15,000 customers across 8 features
- ~7% missing revenue values
- Inconsistent formatting in `sales_method`
- Unrealistic tenure value detected (63 years)
- Slight positive skew in revenue distribution

The dataset was deemed structurally sound with minor, correctable issues.

---

## Exploratory Data Analysis  
**Notebook:** `02_eda.ipynb`

This phase explores customer behavior and revenue patterns to uncover relationships and trends.

### Areas Explored:
- Revenue distribution and skewness
- Sales volume patterns
- Website engagement behavior
- Customer tenure distribution
- Sales strategy comparisons

### Key Observations:
- Revenue shows mild right skew (high-value customers pull the mean upward)
- Most customers purchase between 9–11 units
- Website engagement is stable across segments
- Strategy-based revenue differences begin to emerge

---

## Strategy Performance Analysis  
**Notebook:** `03_analysis.ipynb`

This phase evaluates the relative effectiveness of each sales strategy.

### Focus Areas:
- Revenue comparison across sales methods
- Week-over-week performance trends (Weeks 1–6)
- Statistical comparison of strategies
- Customer behavior segmentation

### Core Insight:
The **Email + Call strategy consistently generates higher revenue** compared to single-channel approaches.

This suggests that multi-touch outreach increases customer conversion and purchase volume.

---

## Key Insights

- Multi-channel outreach outperforms single-channel strategies  
- Revenue distribution shows slight positive skew  
- Minor data quality issues were identified and resolved  
- Short 6-week time horizon limits long-term performance evaluation  

---

## Business Recommendations

1. Prioritize the Email + Call strategy for high-value customers  
2. Standardize sales input formats to prevent category inconsistencies  
3. Extend tracking beyond 6 weeks to evaluate long-term retention  
4. Further segment customers by tenure and engagement level  

---

## Project Status

Completed — end-to-end validation, exploration, and strategic evaluation delivered.










