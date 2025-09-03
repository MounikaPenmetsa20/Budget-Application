# Budget App

This project is a simple **Budget Management System** implemented in Python.  
It allows you to create budget categories (like *Food*, *Clothing*, *Business*), deposit money, withdraw money, transfer funds between categories, and generate a **spending chart** showing the percentage of expenses in each category.

---

## 📂 Project Structure

├── budget.py # Contains the Category class and create_spend_chart function
├── main.py # Runs unit tests (provided by unittest)
├── test_module.py # Entrypoint script to interact with the app and run tests


---

## ⚙️ Features

- **Category class**
  - `deposit(amount, description="")` → Add funds with optional description.
  - `withdraw(amount, description="")` → Remove funds if available.
  - `get_balance()` → Returns current balance of the category.
  - `transfer(amount, category)` → Move funds from one category to another.
  - `check_funds(amount)` → Ensures enough balance before withdrawal/transfer.
  - `__str__()` → String representation of ledger for pretty printing.

- **create_spend_chart(categories)**
  - Generates a **text-based bar chart** showing the percentage of spending per category.

---









