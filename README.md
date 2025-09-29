# 💰 Personal Finance Tracker

A Python-based application to help you **track and manage your personal finances** effortlessly. Keep an eye on your income and expenses and maintain a clear overview of your financial health.

---

## 📌 Features
- Add and track **income and expenses**.
- Records are **saved in a CSV file** for easy storage and backup.
- Simple, intuitive, and modular Python code.
- Clean project structure with **data separated from logic** (`data_entry.py` handles data management).

---

## 📝 Functionality Overview
- Users can enter financial transactions, specifying type (income/expense), amount, and details.
- All transactions are recorded in `finance_data.csv` for persistent storage.
- Modular design makes it easy to extend or modify functionality in the future.

---

## 💡 Example
```text
Enter transaction type: Expense
Enter amount: 500
Enter details: Grocery shopping

Enter transaction type: Income
Enter amount: 2000
Enter details: Salary

Transaction successfully recorded!
```

- The above entries will be stored in `finance_data.csv` like:
```text
Type,Amount,Details
Expense,500,Grocery shopping
Income,2000,Salary
```

---

## 📂 Files
- **main.py** – Entry point of the application.  
- **data_entry.py** – Handles user input and updates the CSV file.  
- **finance_data.csv** – Stores all financial transactions.  
- **.gitignore** – Excludes unnecessary files from version control.  

---

## ⚡ Highlights
- Simple **CSV-based storage**, no database required.
- Easy to maintain and expand.
- Helps you gain **better control over your finances** by keeping all records organized.
