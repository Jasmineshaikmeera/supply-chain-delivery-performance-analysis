# Supply Chain Delivery Performance & Profitability Analysis

## Business Problem
A global e-commerce platform (sporting goods, fitness equipment, footwear, 
apparel) was experiencing frequent delivery delays against scheduled shipping 
windows — eroding customer trust and reducing order profitability.

## Objective
Analyze delivery performance and profitability across 172,765 orders to 
quantify the scale and financial impact of delivery delays.

## Dataset
DataCo Supply Chain Dataset — 180,519 order records, 53 columns 
(customer, product, order, shipping, and profit data).
[Add dataset source link if public, e.g. Kaggle]

## Process
1. Cleaned the dataset: removed PII columns, near-empty fields, and 
   cancelled orders → 172,765 valid orders
2. Engineered a delay metric comparing actual vs. scheduled shipping time
3. Classified orders as Profit / Loss / Break-Even using profit ratios
4. Connected delay and profitability to quantify financial exposure
5. Analyzed delay rates by region, shipping mode, category, and month
6. Identified the operational dimensions with the widest delay-rate swings

## Key Findings
- 54.71% of orders were delivered late
- $2.1M in profit was tied to delayed orders
- 90th percentile delay was 3 days — indicating a systemic, fixable process issue
- Delay rates varied significantly by shipping mode and region

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn

## Files
- `notebooks/supply_chain_performance_analysis.ipynb` — full analysis
- `images/` — exported charts

## Author
Jasmine | [LinkedIn](https://www.linkedin.com/in/shaik-jasmine2002)