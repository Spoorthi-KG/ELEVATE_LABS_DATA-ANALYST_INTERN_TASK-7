# ELEVATE_LABS_DATA-ANALYST_INTERN_TASK-7
# TASK 7 — Basic Sales Summary

This project demonstrates connecting Python to an SQLite database, running SQL queries, and visualizing the results with pandas + matplotlib.

## Files
- `create_db.py` — creates `sales_data.db` and inserts sample sales data
- `sales_summary.py` — runs SQL summary and plots `sales_chart.png`
- `sales_chart.png` — generated chart (created when you run `sales_summary.py`)

## How to Run
1. Run `python create_db.py` (only once) — this creates and populates `sales_data.db`
2. Run `python sales_summary.py` — this will print a sales summary table and save a chart

## Dependencies
- Python 3.8+
- pandas (`pip install pandas`)
- matplotlib (`pip install matplotlib`)
