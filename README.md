# Smart Expense Tracker

A responsive personal finance dashboard built with vanilla HTML, CSS, and JavaScript. It works entirely in the browser and does not require account credentials or external APIs.

## Features
- Record income and expenses with date, category, and description.
- See total balance, income, and expenses.
- Set a monthly spending budget and monitor usage.
- Search transactions and filter by income/expense.
- Review a category-wise expense breakdown.
- Export transactions to CSV for spreadsheet analysis.
- Persist data in browser `localStorage`.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Add transactions and set your monthly budget.

No build tools or package installations are required. For development, open the folder in VS Code and optionally use Live Server.

## Structure
```text
smart-expense-tracker/
├── index.html
├── style.css
├── app.js
└── README.md
```

## Concepts demonstrated
CRUD operations, data modeling, array filtering and aggregation, form validation, CSV generation, localStorage, responsive CSS, and DOM event handling.

## Important note
This is a learning project, not a banking application. It does not connect to bank accounts. Data is stored in the current browser profile; clearing browser storage removes it.

## Future improvements
Monthly reports, charts, recurring transactions, encrypted cloud backup, and an optional API/database backend.

## License
MIT — see `LICENSE`.
