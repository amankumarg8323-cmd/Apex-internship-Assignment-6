# Apex Lark AI & ML Internship – Day 5

## Topic
Data Visualization Using Matplotlib & Seaborn

## Project Overview
This project analyzes an e-commerce dataset to identify sales trends, customer purchasing patterns, relationships between variables, and unusual values.

## Dataset
Online Retail dataset from the UCI Machine Learning Repository.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Visualizations
### Matplotlib
1. Line Chart – Monthly Sales Trend
2. Bar Chart – Top Countries by Sales
3. Histogram – Unit Price Distribution
4. Pie Chart – Sales Contribution
5. Scatter Plot – Quantity vs Unit Price

### Seaborn
1. Count Plot
2. Box Plot
3. Violin Plot
4. Pair Plot
5. Distribution Plot
6. Correlation Heatmap

## Key Insights
- Sales patterns can be studied over time using monthly sales trends.
- Sales are concentrated among a smaller group of countries.
- Product prices and transaction values are typically skewed, with some unusually large values.
- Quantity and total sales are related because transaction value is calculated using quantity and unit price.
- Outlier detection helps identify unusual purchases or possible data-quality issues.

## Business Recommendations
1. Focus marketing efforts on high-performing markets.
2. Maintain inventory for consistently high-demand products.
3. Investigate extreme transactions and values.
4. Use sales trends for inventory and campaign planning.
5. Use purchasing patterns to support targeted offers and cross-selling.

## How to Run
Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

Then open the `.ipynb` file in Jupyter Notebook or run the Python script.
