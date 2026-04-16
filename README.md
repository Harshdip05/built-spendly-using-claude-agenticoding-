# Spendly

A personal finance tracking web application built with Flask. Track expenses, understand spending patterns, and take control of your financial life.

## Features

- **User Authentication** - Register and login with email and password
- **Expense Tracking** - Log expenses with category, amount, date, and description
- **Spending Insights** - View category breakdowns and monthly summaries
- **Time Period Filtering** - Filter expenses by date range

## Tech Stack

- **Backend**: Flask (Python)
- **Database**: SQLite
- **Frontend**: Jinja2 templates, vanilla JavaScript
- **Styling**: Custom CSS with CSS variables

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Harshdip05/built-spendly-using-claude-agenticoding-.git
   cd expense-tracker
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   ```

3. Activate the virtual environment:
   ```bash
   # Windows
   venv\Scripts\activate
   # macOS/Linux
   source venv/bin/activate
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the application:
   ```bash
   python app.py
   ```

6. Open your browser and navigate to `http://localhost:5001`

## Project Structure

```
expense-tracker/
├── app.py                 # Flask application and routes
├── database/
│   └── db.py              # Database utilities
├── static/
│   ├── css/
│   │   └── style.css      # Application styles
│   └── js/
│       └── main.js        # Client-side JavaScript
├── templates/
│   ├── base.html          # Base template
│   ├── landing.html       # Landing page
│   ├── login.html         # Login page
│   └── register.html      # Registration page
├── requirements.txt       # Python dependencies
└── CLAUDE.md              # Development guide
```

## License

MIT
