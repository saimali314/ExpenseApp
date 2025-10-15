# 💰 ExpenseApp — PyQt6 + SQLite (QtSql)

A desktop expense tracker built with **Python (PyQt6)** and **SQLite** (via Qt’s `QSqlDatabase`).  
Add, view, and delete expenses with a clean GUI.

---

## ✨ Features
- 📅 Add expenses with date, category, amount, and description
- 🗂 Default categories: Food, Rent, Bills, Entertainment, Shopping, Other
- 📋 Live table view with stretchable columns
- 🗑 Delete selected expense rows
- 🎨 Polished styling using Qt stylesheets
- 💾 Data stored locally in `expenses.db` (auto-created)

---

## 🧱 Project Structure
ExpenseApp/
├── app.py # GUI (widgets, styling, table, signals/slots)
├── database.py # DB init + CRUD using QSqlDatabase/QSqlQuery
├── main.py # Application entry point
├── requirements.txt
└── README.md

## 🧰 Prerequisites
- Python **3.10–3.12** recommended
- OS: Windows/macOS/Linux

> **Note:** `sqlite3` is built into Python. Qt’s SQLite driver (`QSQLITE`) comes with PyQt6.

---


## 🚀 Setup & Run

### 1) Clone and enter the project
```bash
git clone https://github.com/saimali314/ExpenseApp.git
cd ExpenseApp
```
### 2️) Create & activate a virtual environment

<b>Windows (PowerShell):</b>

python -m venv .venv
.\.venv\Scripts\activate


<b>macOS/Linux:</b>

python3 -m venv .venv
source .venv/bin/activate

### 3) Install dependencies
pip install -r requirements.txt

### 4) Run the application
python main.py

---

## 🖼️ Screenshots
![Main Window](screenshots/ExpenseApp.png)
![Main Window](screenshots/ExpenseApp2.png)
