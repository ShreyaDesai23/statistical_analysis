# 📊 Statistical Business Analysis

## 🔹 Project Overview
This project performs statistical analysis on business sales data to extract meaningful insights related to revenue generation, pricing impact, and regional performance.

The goal is to apply core statistical techniques such as:
- Descriptive statistics
- Hypothesis testing
- Correlation analysis
- Confidence intervals
- Regression modeling

to support data-driven business decisions.

---

## 🔹 Dataset Description
The dataset (`sales_data.csv`) contains 100 records with the following key features:

- Quantity → Number of units sold
- Price → Price per unit
- Total_Sales → Revenue generated
- Region → Sales region (East, West, etc.)

---

## 🔹 Setup Instructions

### 1. Clone Repository
- git clone https://github.com/ShreyaDesai23/statistical_analysis.git
- cd statistical-analysis-project

### 2. Install Dependencies
- pip install -r requirements.txt

### 3. Run Script
- python statistical_analysis.py

## 🔹 Technical Implementation
1. Descriptive Statistics
- Mean, Median, Standard Deviation calculated
- Helps understand distribution and variability

---

2. Confidence Interval
- 95% confidence interval computed using t-distribution
- Provides estimate reliability

---

3. Correlation Analysis
- Pearson correlation between:
- Price and Sales
- Quantity and Sales
- Heatmap visualization included

---

4. Hypothesis Testing
Test 1: One-Sample T-Test
Objective: Check if mean sales differ from zero
Test 2: Independent T-Test
Objective: Compare sales between East and West regions
Test 3: Pearson Correlation Test
Objective: Check statistical significance of relationship between price and sales

---

5. Regression Analysis
Linear regression using:
Price
Quantity
Target variable: Total Sales
Model used:
- Ordinary Least Squares (OLS)

## 🔹 Results Summary
Refer to report:
### Key Findings:
Strong positive correlation between:
- Price and Sales (0.65)
- Quantity and Sales (0.69)
Hypothesis tests show:
- Sales are statistically significant
- Regional differences exist
- Price significantly impacts sales

## 🔹 Business Insights
Increasing product quantity sold improves revenue
Pricing strategy directly affects sales performance
Regional differences suggest targeted strategies

## 🔹 Visualizations
Histogram & distribution plots
Correlation heatmap
Regression plot (Price vs Sales)

## 🔹 Limitations
Assumes linear relationships
No feature engineering performed
Limited dataset size (100 records)

## 🔹 Future Improvements
Add time-series analysis
Include more business variables
Use advanced models (e.g., ML regression)

## 🔹 Conclusion
The analysis confirms that both pricing and quantity significantly influence revenue. Statistical methods provide strong evidence for optimizing business strategies based on data insights.
