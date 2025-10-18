# SQL Transaction Dashboard – Module 2 (Python for Finance Foundation)

This project demonstrates how to use **SQL with Python (SQLite + Pandas)** for financial data analysis.  
We load a sample transactions dataset into a database, run SQL queries for insights, and visualize results with Python.

---

## 🔑 Skills Covered
- SQL Basics: `SELECT`, `WHERE`, `GROUP BY`, `ORDER BY`
- JOINs (`INNER JOIN`, `LEFT JOIN`)
- Aggregations & Time-Series Analysis
- Window Functions (rolling sums, fallback with Pandas)
- Python + SQL Integration (SQLite via SQLAlchemy)
- Data Export for downstream use

---

## 📂 Project Structure
- `transactions.csv` → sample input dataset
- `transactions.db` → SQLite database file (auto-created)
- `SQL_Transaction_Dashboard.ipynb` → main notebook
- `transactions_cleaned.csv` → cleaned export for reuse

---

## 🛠️ Step-by-Step Workflow

### Step 1 – Setup & Database Creation
- Import libraries: `pandas`, `sqlite3`, `sqlalchemy`, `matplotlib`, `seaborn`
- Create SQLite database `transactions.db`
- Load `transactions.csv` into table `transactions`

### Step 2 – Preview Data
- Explore first few rows of transactions

### Step 3 – SQL Basics: SELECT & WHERE
- Example: view all `Food & Dining` transactions

### Step 4 – Aggregations: GROUP BY & ORDER BY
- Calculate total spend, average spend, and transaction counts per category

### Step 5 – Daily Spend Analysis
- Group by date → daily spend
- Line chart visualization

### Step 6 – JOINs
- **INNER JOIN**: enrich transactions with category groups
- **LEFT JOIN**: add loyalty program table (with missing matches)

### Step 7 – Rolling Sums
- 7-day rolling spend (via Pandas)

### Step 8 – Top Merchants
- Rank top 10 merchants by total spend
- Bar chart visualization

### Step 9 – Export Clean Dataset
- Save cleaned dataset as `transactions_cleaned.csv`

---

## 📊 Visualizations
(Add screenshots here after running the notebook)

- Daily Spend Trend  
- Daily Spend + 7-day Rolling Sum  
- Category Spend Breakdown  
- Top Merchants by Spend

<img width="1196" height="585" alt="Daily-Spend-Analysis" src="https://github.com/user-attachments/assets/d8f3e721-5448-4faf-a6ca-3dbd3dd4b5e8" />

<img width="1167" height="583" alt="Rolling-Sums" src="https://github.com/user-attachments/assets/0174a714-8f3b-463b-96cd-95faa25a090c" />

<img width="1184" height="655" alt="Top-Merchants" src="https://github.com/user-attachments/assets/f91bf1bd-7885-4082-8661-9c39881638c2" />

---

## 📈 Example Outputs

**Category Spend Summary**
| Category       | Tx Count | Total Spent | Avg Spend |
|----------------|----------|-------------|-----------|
| Shopping       | 5        | 1440.45     | 288.09    |
| Utilities      | 3        | 210.75      | 70.25     |
| Transport      | 4        | 49.45       | 12.36     |
| Food & Dining  | 6        | 49.30       | 8.22      |
| Entertainment  | 2        | 25.98       | 12.99     |

---

## ✅ Summary
This project replicates a **basic transaction analytics dashboard** like those used in personal finance apps and FinTech platforms.  
We combined SQL querying power with Python visualization to analyze spending patterns, category distributions, and merchant insights.
