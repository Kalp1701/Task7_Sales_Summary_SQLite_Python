# Task 7: Sales Summary using SQLite and Python

## 📌 Objective
Use SQL inside Python to pull basic sales information like **total quantity sold** and **total revenue**, and display the results using print statements and a **bar chart**.

---

## 🛠 Tools Used
- Python
- SQLite (`sqlite3`)
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📂 Files Included
- `task7_sales_summary.ipynb` - Jupyter notebook with full code
- `sales_data.db` - SQLite database containing sample sales data
- `sales_chart.png` - Bar chart showing revenue per product (generated via Matplotlib)
- `README.md` - This file

---

## 📊 Dataset Structure
The SQLite database contains a single table named `sales` with the following columns:
- `product` (TEXT)
- `quantity` (INTEGER)
- `price` (REAL)

Sample records were inserted manually for demonstration.

---

## ✅ Key Operations
- Connected to SQLite database using `sqlite3`
- Executed SQL query to calculate total quantity and revenue per product
- Loaded query results into a Pandas DataFrame
- Printed tabular output using `print(df)`
- Visualized revenue using a bar chart (`matplotlib`)
- Saved the chart as `sales_chart.png`

---

## 📈 Output Example

A table and a bar chart showing total quantity and revenue per product.

---

## 🧠 Outcome
Learned how to combine SQL and Python to:
- Extract data from a SQLite database
- Summarize key metrics using SQL
- Present results visually using Matplotlib

---

## 📥 How to Run
1. Clone the repository or download the files.
2. Open `task7_sales_summary.ipynb` in Jupyter Notebook.
3. Run all cells to reproduce results and visuals.

---

