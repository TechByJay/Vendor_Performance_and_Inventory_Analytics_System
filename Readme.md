# Vendor Performance & Inventory Analytics System

## Overview

The **Vendor Performance & Inventory Analytics System** is an end-to-end data analytics project focused on analyzing vendor performance, brand profitability, inventory efficiency, and purchasing behavior in the retail and wholesale beverage industry.

This project combines **SQL, Python, statistical analysis, and dashboard visualization** to transform raw business data into actionable business insights for smarter procurement, inventory management, and pricing decisions.

---

# Business Problem

Effective inventory and vendor management are critical for improving profitability in the beverage retail and wholesale industry.

Businesses often face challenges such as:

- Excess unsold inventory
- Vendor dependency
- Low inventory turnover
- Inefficient procurement strategies
- Poor pricing optimization

This project helps answer important business questions such as:

- Which vendors and brands contribute the most to sales and profit?
- Which products need promotional or pricing adjustments?
- Does bulk purchasing reduce unit cost?
- How much capital is locked in unsold inventory?
- Do high-performing and low-performing vendors differ significantly in profitability?

---

# Project Objectives

- Identify top-performing and low-performing vendors and brands
- Analyze vendor contribution to total sales and purchases
- Measure inventory efficiency and stock turnover
- Detect unsold inventory and locked capital
- Analyze the impact of bulk purchasing on unit pricing
- Compare vendor profitability using statistical testing
- Build an interactive dashboard for business decision-making

---

# Tools & Technologies Used

## Programming & Analytics
- Python
- Pandas
- NumPy
- SciPy
- SQLAlchemy

## Data Visualization
- Matplotlib
- Seaborn
- Power BI

## Database
- PostgreSQL

## Development Environment
- Jupyter Notebook
- VS Code

---

# Project Workflow

## 1. Data Extraction

Connected Python with PostgreSQL using SQLAlchemy and extracted data from multiple business tables including:

- `sales`
- `purchases`
- `purchase_prices`
- `vendor_invoice`
- `inventory`

---

## 2. Exploratory Data Analysis (EDA)

Performed extensive exploratory analysis to understand:

- Sales trends
- Purchase behavior
- Freight cost variation
- Inventory turnover patterns
- Vendor contribution
- Profitability distribution
- Outliers and anomalies

### Analysis Techniques Used
- Histograms
- Box plots
- Scatter plots
- Correlation analysis
- Summary statistics

---

## 3. Data Cleaning & Feature Engineering

Created multiple business KPIs and analytical metrics such as:

| Metric | Description |
|---|---|
| Gross Profit | Sales - Purchase Cost |
| Profit Margin | Profit percentage generated |
| Stock Turnover | Inventory movement efficiency |
| Sales/Purchase Ratio | Procurement efficiency |
| Unsold Inventory Value | Capital tied in unsold inventory |
| Purchase Contribution % | Vendor contribution to total purchases |

---

## 4. Vendor & Brand Analysis

Analyzed vendors and brands based on:

- Total Sales
- Total Purchase Value
- Gross Profit
- Profit Margin
- Purchase Contribution
- Inventory Turnover
- Unsold Capital

The analysis identified:
- High-performing vendors
- Low-performing vendors
- Top-selling brands
- Slow-moving products

---

## 5. Statistical Analysis

Applied statistical methods to validate business assumptions and compare vendor groups.

### Techniques Used
- Confidence Interval Analysis
- Hypothesis Testing
- Independent Sample T-Test

### Objective
To compare profitability behavior between:
- Top-performing vendors
- Low-performing vendors

---

# Key Insights & Findings

## Vendor Insights

- **DIAGEO NORTH AMERICA INC** emerged as the leading vendor by total sales.
- Other top vendors include:
  - MARTIGNETTI COMPANIES
  - PERNOD RICARD USA
  - JIM BEAM BRANDS COMPANY

### Vendor Concentration

The top 10 vendors contribute approximately:

```text
65.69% of total purchase contribution
```

This indicates strong dependency on a limited set of vendors.

---

## Brand Insights

Top-selling brands include:

- Jack Daniels No 7 Black
- Tito's Handmade Vodka
- Grey Goose Vodka
- Captain Morgan Spiced Rum

Several low-selling brands showed:
- Higher profit margins
- Lower sales volume

This indicates opportunities for:
- Better pricing strategies
- Promotional campaigns
- Product repositioning

---

## Inventory Insights

### Unsold Capital

Approximate unsold inventory value:

```text
$2.71 Million
```

This represents significant capital tied up in slow-moving inventory.

### Inventory Issues Identified
- Overstocking
- Slow inventory turnover
- High holding costs

---

## Bulk Purchasing Analysis

Bulk purchasing significantly reduces unit cost.

| Purchase Volume | Average Unit Cost |
|---|---|
| Small Orders | 39.07 |
| Medium Orders | 15.49 |
| Large Orders | 10.78 |

### Conclusion
Larger purchase volumes reduce procurement cost substantially.

---

## Statistical Findings

The analysis revealed:

- Low-performing vendors have higher average profit margins than top-performing vendors.
- The difference in profit margins is statistically significant.

### T-Test Result

```text
p-value < 0.001
```

This confirms that the difference between vendor groups is not random.

---

# Dashboard Features

The dashboard provides interactive business insights including:

- Total Sales
- Total Purchases
- Gross Profit
- Profit Margin
- Unsold Inventory Value
- Vendor Contribution Analysis
- Top Vendors by Sales
- Top Brands by Sales
- Low-Performing Vendor Analysis
- Profitability Scatter Analysis

---

# Dashboard Preview

![Dashboard Preview](https://github.com/TechByJay/Vendor_Performance_and_Inventory_Analytics_System/blob/master/Vendor_Performance_and_Inventory_Analytics_System.jpeg)

---

# Business Recommendations

## Procurement Optimization
- Reduce over-dependence on a few vendors
- Diversify procurement sources

## Pricing Strategy
- Promote high-margin low-selling products
- Re-evaluate pricing for underperforming brands

## Inventory Management
- Monitor slow-moving inventory regularly
- Reduce excess stock holding

## Cost Optimization
- Utilize bulk purchasing where demand forecasting supports it
- Optimize freight and procurement costs

## Vendor Strategy
- Focus on vendor profitability rather than only sales volume
- Re-negotiate contracts with low-efficiency vendors

---


# How to Run the Project

## 1. Clone the Repository

```bash
git clone https://github.com/TechByJay/Vendor_Performance_and_Inventory_Analytics_System.git
```

---

## 2. Install Required Libraries

```bash
pip install -r requirements.txt
```

---

## 3. Configure PostgreSQL Database

Update database credentials inside the notebook or configuration file.

---

## 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Run:
- EDA notebook first
- Analysis notebook second

---

# Future Improvements

Possible future enhancements:

- Machine Learning-based sales forecasting
- Demand prediction models
- Real-time dashboard integration
- Automated anomaly detection
- Vendor recommendation system
- AI-powered inventory optimization

---

# Conclusion

This project demonstrates how SQL, Python, statistical analysis, and dashboard visualization can be combined to solve real-world business problems in inventory and vendor management.

The system helps businesses:
- Improve profitability
- Optimize procurement
- Reduce inventory waste
- Make data-driven decisions

---

# Author

## Jay Vasant Rande

- Email: jayrandecs@gmail.com
- LinkedIn: https://www.linkedin.com/in/jay-rande/

---

---

