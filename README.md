# Daily-Expense-Tracker-with-Functional-Tools
The Daily Expense Tracker with Functional Tools is a Python-based mini project that allows users to track their daily expenses using the power of functional programming.
Project Description:
The Daily Expense Tracker with Functional Tools is a Python-based mini project that allows users to track their daily expenses using the power of functional programming. Users can input expenses with categories and dates, and the tool filters, groups, and summarizes the data using lambda, map, filter, reduce, decorators, and generators.

This project not only helps in personal finance management but also demonstrates how to handle real-world data processing tasks efficiently and cleanly using functional programming concepts in Python.

Skills Required:
Python Basics (Variables, Lists, Dictionaries, Functions)

Functional Programming:

Pure Functions

Lambda Functions

map(), filter(), reduce()

Decorators

Generators

Date Handling with datetime

Data Aggregation & Summarization

Future Updation Ideas:
Export expense report to CSV or Excel

Add persistent storage using JSON or SQLite

Integrate a monthly budget limit feature

Create pie charts or bar graphs for visual summaries

Add a simple CLI or GUI using Tkinter

Implement login and multi-user tracking

Web integration with Flask or Django

Recurring expense tracking (e.g., subscriptions)

Algorithm Steps:
Accept expense inputs as (amount, category, date).

Store in a list of dictionaries.

Use a generator to yield expense entries.

Use filter to find expenses by category or date range.

Use map to extract amounts or dates.

Use reduce to calculate total expenses.

Decorate processing functions for logging or validation.


Sample Output:
yaml
CopyEditExecuting: summarize_expenses
Category: All | Total Expenses: $895
Details:
- 2025-05-01 | Groceries | $250
- 2025-05-02 | Transport | $120
- 2025-05-01 | Rent | $300
- 2025-05-03 | Entertainment | $75
- 2025-05-03 | Transport | $50
- 2025-05-04 | Groceries | $100
Completed in 0.0003 seconds
 
Executing: summarize_expenses
Category: Transport | Total Expenses: $170
Details:
- 2025-05-02 | Transport | $120
- 2025-05-03 | Transport | $50
Completed in 0.0002 seconds

Output daily, weekly, or category-wise summaries.

