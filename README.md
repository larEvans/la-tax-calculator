# Create the README.md file in the notebook environment
readme_content = """# LA Tax & Budget Calculator

A multi-step Flask web application to calculate Louisiana self-employment taxes on 1099-NEC income, track expenses, and generate monthly/yearly statements and Excel reports.

---

## Features

- **Multi-step workflow**  
  1. Enter number of checks  
  2. Enter gross amounts, income type, and date  
  3. Calculate SE, federal & state tax breakdown  
  4. Add/edit expenses per check  
  5. View final net profit and export to Excel  
- **Persistent entries**  
  - Save named entries in SQLite  
  - View, edit, delete saved entries  
  - Export individual entries to `.xlsx`  
- **Statements dashboard**  
  - Month-by-month summary of income, expenses, and taxes  
  - Yearly aggregates  
  - Filter by income type (e.g. 1099-NEC, W-2)  
  - Export all statements to Excel  

---

## Prerequisites

- Python 3.8+  
- Git  
- (optional) Virtual environment tool (`venv`, `virtualenv`, etc.)

---

## Installation

1. **Clone the repo**  
   ```bash
   git clone git@github.com:larEvans/la-tax-calculator.git
   cd la-tax-calculator
