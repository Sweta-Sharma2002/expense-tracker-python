# 💸 Expense Tracker — Python

A console-based personal expense management system built with Python.
Records daily expenses by category, stores data persistently in a CSV file,
and generates spending summaries and visualizations using Pandas and Matplotlib.

---

## 🚀 Features

- Add expense entries with date, category, amount, and description
- Persistent storage using CSV — data is saved and available across sessions
- Category-wise expense breakdown (Food, Transport, Shopping, etc.)
- Monthly total calculation
- Bar chart visualization of spending by category using Matplotlib

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Python 3.x | Core programming language |
| Pandas | Data loading, grouping, and aggregation |
| Matplotlib | Bar chart visualization |
| CSV | Persistent file-based storage |
| OOP | Modular class-based code design |

---

## ▶️ How to Run

**Option 1 — Run locally:**

```bash
git clone https://github.com/Sweta-Sharma2002/expense-tracker-python.git
cd expense-tracker-python
pip install pandas matplotlib
jupyter notebook Expense_Tracker.ipynb
```

**Option 2 — Run on Google Colab (no installation needed):**

Open [Google Colab](https://colab.research.google.com), click `File → Open notebook → GitHub`, paste the repo URL and open `Expense_Tracker.ipynb`.

---

## 📁 Project Structure

expense-tracker-python/
├── Expense_Tracker.ipynb   # Main notebook — all logic here
├── expenses.csv            # Sample expense data (input/output)
└── README.md

---

## ⚙️ How It Works

1. **Add Expense** — Enter date, category, amount, and a short description. The entry is appended to `expenses.csv` immediately.
2. **Load & Process** — Pandas reads `expenses.csv` and computes totals and category-wise breakdowns using `groupby` and aggregation.
3. **Visualize** — Matplotlib generates a bar chart showing spending distribution across categories.
4. **Persistent Storage** — All data is stored in `expenses.csv`. Close the notebook and reopen — your data is still there.

---

## 📊 Sample Output

| Category | Total Spent |
|---|---|
| Food | ₹3,200 |
| Transport | ₹1,450 |
| Shopping | ₹2,800 |
| Utilities | ₹900 |
| **Total** | **₹8,350** |

A bar chart is auto-generated from this data.

---

## 🧠 What I Learned

- Designing modular OOP code — separate classes for transactions, reporting, and file I/O
- CSV-based data persistence without any external database
- Pandas groupby and aggregation for financial summaries
- Matplotlib bar chart generation from grouped data
- Handling edge cases — empty file, invalid input, missing categories

---

## 🔮 Future Improvements

- MySQL database integration for multi-user support
- Budget alert when spending crosses a set monthly limit
- Monthly comparison charts (this month vs last month)
- Simple web interface using Flask

---

## 👩‍💻 Author

**Sweta Sharma**  

[![GitHub](https://img.shields.io/badge/GitHub-Sweta--Sharma2002-181717?style=flat&logo=github)](https://github.com/Sweta-Sharma2002)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-swetasharma-0077B5?style=flat&logo=linkedin)](https://linkedin.com/in/swetasharma)
[![Email](https://img.shields.io/badge/Email-swetashr08@gmail.com-D14836?style=flat&logo=gmail)](mailto:swetashr08@gmail.com)
