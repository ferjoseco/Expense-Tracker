Expense Tracker
A Python-based expense tracking application with database storage and data visualization capabilities.

Overview
This Expense Tracker helps businesses and individuals monitor their spending through an interactive command-line interface. The application categorizes expenses, stores them in a SQLite database, and provides visual analytics through bar charts and pie charts.

Features
Expense Management: Add, edit, and delete expenses with categories

Data Visualization: Generate bar charts and pie charts for expense analysis

Database Storage: Persistent storage using SQLite

Smart Categorization: Automatic "low expense" classification for amounts under 100

Business Categories: Overhead, salaries, marketing, and low expense tracking

Technical Stack
Python 3 - Core programming language

SQLite - Database management

Matplotlib - Data visualization

Seaborn - Enhanced chart styling

NumPy - Mathematical operations

Installation
Clone the repository:

bash
git clone https://github.com/ferjoseco/Expense-Tracker.git
cd Expense-Tracker
Install required dependencies:

bash
pip install matplotlib seaborn numpy
Run the application:

bash
python Final_Version_Expense_Tracker.ipynb
Or open in Google Colab using the badge above.

Usage
The application provides a menu-driven interface with the following options:

Add Expense - Record new expenses with amount, category, and date

Edit Expense - Modify existing expense records

Delete Expense - Remove expenses from the database

View Expenses - Display all recorded expenses in table format

Bar Chart - Visualize expenses by category as a bar graph

Pie Chart - Show expense distribution as a pie chart

Exit - Close the application

Expense Categories
Overhead - Operational costs

Salaries - Employee compensation

Marketing - Advertising and promotion

Low Expense - Automatic classification for amounts under 100

Database Schema
The SQLite database uses a simple table structure:

sql
expenses (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    amount INTEGER NOT NULL,
    category TEXT NOT NULL,
    date TEXT NOT NULL
)
Visual Features
Bar Charts: Category-wise expense comparison in "Shrek green" (#B0C400)

Pie Charts: Expense distribution with HSV color palette

Interactive Display: Non-blocking charts for seamless workflow

Error Handling
Input validation for numerical values

Category verification

Date format checking

Expense ID existence confirmation

Project Structure
text
Expense-Tracker/
├── Final_Version_Expense_Tracker.ipynb
├── expenses.db (created automatically)
└── README.md
License
This project is open source and available under the MIT License.
