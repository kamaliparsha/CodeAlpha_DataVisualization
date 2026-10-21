# CodeAlpha Data Visualization — Online Retail Sales

## Project Overview
This project visualizes online retail sales data using Python. It explores monthly revenue trends, top products, country-wise revenue, and the distribution of daily revenue.

## Internship
Completed as part of the CodeAlpha Data Analytics Internship — Task 3: Data Visualization.

## Dataset
**Source:** UCI Machine Learning Repository — Online Retail  
https://archive.ics.uci.edu/dataset/352/online+retail

The original dataset contains 541,909 records and eight columns.

## Tools and Technologies
- Python
- Pandas and NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

## Visualizations
1. Monthly Retail Revenue Trend
2. Top 10 Products by Revenue
3. Top 10 Countries by Revenue
4. Distribution of Daily Retail Revenue

## Data Preparation
- Removed duplicate records.
- Removed rows missing essential analysis fields.
- Excluded cancelled invoices.
- Excluded transactions with non-positive quantities or unit prices.
- Calculated revenue as `Quantity × UnitPrice`.

## Key Findings
- The cleaned dataset contains 524,878 transactions.
- Total revenue is approximately £10,642,110.80.
- The United Kingdom generated the highest country-level revenue.
- November 2011 had the highest monthly revenue in the analyzed data.
- Daily revenue is right-skewed, with a small number of unusually high-revenue days.

These results depend on the cleaning rules used. December 2011 contains only partial-month data, so it should not be compared directly with complete months.

## How to Run
1. Open `CodeAlpha_DataVisualization.ipynb` in Google Colab.
2. Download the Excel dataset from the UCI link above.
3. Upload the Excel file when prompted.
4. Run the notebook cells in order.

Required packages:
```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

## Project Files
- `CodeAlpha_DataVisualization.ipynb` — analysis and visualizations
- `README.md` — project documentation

The notebook also generates PNG charts and CSV summary files in an `outputs` folder. These are created in the runtime when the notebook is executed.

## Acknowledgements
Dataset provided by the UCI Machine Learning Repository for educational and analytical use.
