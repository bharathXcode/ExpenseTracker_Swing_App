# 💸 Expense Tracker (Java Swing)

**Author**: Bharath L  
**Technology**: Java Swing (Desktop GUI Application)  
**License**: MIT License  
**Status**: Completed ✅

---

## 📘 Overview

The **Expense Tracker** is a lightweight desktop application built using **Java Swing** that allows users to track personal expenses. Users can input categories, amounts, and dates of expenses. The application displays all entries in a table and calculates the running total automatically.

---

## ✨ Features

- 📝 Add new expense entries (category, amount, date)
- 📅 Auto-fills the current date by default
- 📊 Displays a table of all expenses
- ❌ Delete selected entries from the table
- 🔢 Automatically calculates and updates the total amount
- 🧠 Simple and intuitive UI
- 🚫 Handles invalid input with error messages

---

## 📂 Project Structure

```
ExpenseTracker/
├── ExpenseTracker.java       # Main application source code
```

---

## 📦 Requirements

- Java JDK 8 or higher
- No external libraries required (uses built-in Java Swing)

---

## 🚀 How to Run

1. **Compile the Code**

   Open a terminal or command prompt in the project directory and run:

   ```bash
   javac ExpenseTracker.java
   ```

2. **Run the Program**

   ```bash
   java ExpenseTracker
   ```

---

## 🛠️ How to Use

1. Launch the application.
2. Select a category (Food, Transport, Bills, etc.).
3. Enter the amount and date (or use the default current date).
4. Click **"Add Expense"** to add it to the table.
5. To remove an entry, select a row and click **"Delete Selected"**.
6. The total will update automatically at the bottom.

---
## Output



<img width="1918" height="1016" alt="Output" src="https://github.com/user-attachments/assets/48b2f4b8-098d-4ade-a98c-62fe4c268f1c" />


---

## 📝 Notes

- The total is recalculated whenever you add or remove an entry.
- The "Amount" field must be a valid number, or you’ll see an error.
- Dates must follow the format: `YYYY-MM-DD`.

---

## 🖼️ UI Preview (Text Description)

- Left side: Input form with dropdown, amount field, date field, and two buttons.
- Center: Expense table showing Category | Amount | Date.
- Bottom-right: Total display (`Total: 0.0` or more).

---

## 📃 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

---
