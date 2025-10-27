# Expense Tracker

A Python-based expense tracking application with database storage and data visualization capabilities.

## Overview

This Expense Tracker helps businesses and individuals monitor their spending through an interactive command-line interface. The application categorizes expenses, stores them in a SQLite database, and provides visual analytics through bar charts and pie charts.

## Features

- Expense Management: Add, edit, and delete expenses with categories
- Data Visualization: Generate bar charts and pie charts for expense analysis
- Database Storage: Persistent storage using SQLite
- Smart Categorization: Automatic "low expense" classification for amounts under 100
- Business Categories: Overhead, salaries, marketing, and low expense tracking

## Technical Stack

- Python 3 - Core programming language
- SQLite - Database management
- Matplotlib - Data visualization
- Seaborn - Enhanced chart styling
- NumPy - Mathematical operations

## Usage

The application provides a menu-driven interface with the following options:

1. **Add Expense** - Record new expenses with amount, category, and date
2. **Edit Expense** - Modify existing expense records
3. **Delete Expense** - Remove expenses from the database
4. **View Expenses** - Display all recorded expenses in table format
5. **Bar Chart** - Visualize expenses by category as a bar graph
6. **Pie Chart** - Show expense distribution as a pie chart
7. **Exit** - Close the application

## Expense Categories

- **Overhead** - Operational costs and general business expenses
- **Salaries** - Employee compensation and payroll expenses
- **Marketing** - Advertising, promotion, and campaign costs
- **Low Expense** - Automatic classification for amounts under 100 units

## Visual Features

- **Bar Charts**: Category-wise expense comparison displayed in "Shrek green" (#B0C400)
- **Pie Charts**: Expense distribution visualization using HSV color palette
- **Interactive Display**: Non-blocking charts that allow continuous program usage
- **Automatic Percentage Labels**: Pie charts display exact percentage distributions
- **Professional Styling**: Clean, readable charts with proper titles and labels

## Error Handling

- **Input Validation**: Ensures numerical values for amounts and IDs
- **Category Verification**: Validates expense categories against approved list
- **Date Format Checking**: Confirms proper date format (YYYY-MM-DD)
- **ID Existence Confirmation**: Verifies expense IDs exist before editing/deleting
- **Menu Input Protection**: Handles invalid menu selections gracefully
- **Database Integrity**: Maintains data consistency during all operations

## Installation

1. Clone the repository:
```bash
git clone https://github.com/ferjoseco/Expense-Tracker.git
cd Expense-Tracker

