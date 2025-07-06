# Task 7: Sales Data Analysis using SQLite and Python

## Objective
Extract and visualize simple sales metrics (total quantity sold and total revenue) from a SQLite database using Python, SQL, Pandas, and Matplotlib.

---

## Dataset
- SQLite database: `sales_data.db`
- Table: `sales`
- Columns:
  - `product` (TEXT)
  - `total_qty` (INTEGER)
  - `revenue` (REAL)

---

## Tools Used
- Python (with built-in `sqlite3`)
- `pandas` for data handling
- `matplotlib` for plotting
- SQLite for storing and querying sales data

---

## Steps Performed
1. Created and connected to `sales_data.db` using `sqlite3`
2. Created a `sales` table and inserted sample data
3. Ran an SQL query to calculate:
   - Total quantity sold per product
   - Total revenue per product (`quantity * price`)
4. Loaded SQL results into a Pandas DataFrame
5. Printed the result using `print()`
6. Plotted a bar chart to visualize revenue by product
7. Saved the chart as `sales_chart.png`

---

## Output
**Console Output:**
```
  product  total_qty  revenue
  Apples         15     37.5
  Bananas        30     30.0
  Oranges        25     45.0
```

**Bar Chart:**
- Displays `revenue` for each `product` using `matplotlib`

---

## Files Included
- `sales_analysis.ipynb` – Python script
- `sales_data.db` – SQLite database file
- `sales_chart.png` – Bar chart image (auto-generated)

---

## How to Run
```bash
python sales_analysis.py
```

---
