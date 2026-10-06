# Retail Sales Analysis

A portfolio project using Python and SQL to analyse retail sales during 2021.

## Tools
Python, pandas, SQLite, Matplotlib, and Jupyter notebooks.

## Workflow
- Cleaned sales data and checked missing values and duplicates.
- Loaded 641,798 cleaned records into SQLite.
- Analysed total sales, monthly trends, top stores, top products, and sales channels.
- Created monthly sales and channel comparison charts.

## Key Findings
- Total sales value: 73,209,782.99.
- Units sold: 1,677,123.
- January had the highest sales; November had the lowest.
- Stores contributed 41.3% of total sales.
- Store 41 and product SKU 1035 led their respective sales rankings.

## Files
- `notebooks/01_data_cleaning.ipynb`: data cleaning.
- `sql/02_sql_analysis.ipynb`: SQL analysis, charts, and findings.
- `requirements.txt`: Python dependencies.

## Run
1. Install dependencies: `pip install -r requirements.txt`.
2. Place `bm_sales.csv` in `data/raw/`.
3. Run the cleaning notebook, then the SQL analysis notebook.

Data files and the generated SQLite database are excluded from Git.

## Limitations
Sales values use the dataset's original monetary units.
Results describe the cleaned records; they do not explain what caused sales differences.