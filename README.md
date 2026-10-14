# Closing Worksheet

A simple web-based calculator for tracking income and expenses at dance events.

## Features

- **Cash Counting**: Enter bill counts for each denomination ($100, $50, $20, $10, $5, $1) with automatic subtotals
- **Electronic Payments**: Track non-cash income separately
- **Artist Payments**: Record contract rates for caller, sound engineer, and up to 5 band members
- **Venue Rent**: Configurable rent expense
- **Automatic Calculations**: All totals update instantly as you type
- **Bonus Calculator**: Computes 10% bonus on positive net income, rounded to the nearest number ending in 0 or 5
- **Mobile Friendly**: Responsive layout works on phones and tablets
- **Dark Mode**: Automatically adapts to system light/dark mode preference
- **Easy Input**: Clicking/tapping an input field selects its contents for quick editing

## Usage

Open `docs/index.html` in any web browser. No server or installation required.

## Default Values

- Caller, Sound, Band members 1-2: $75 each
- Rent: $250

## Calculations

- **Total Cash** = Sum of all bill denominations
- **Income** = Total Cash + Electronic Payments
- **Total Artists** = Sum of all artist contract rates
- **Expenses** = Total Artists + Rent
- **Net Income** = Income - Expenses
- **Bonus** = 10% of Net Income (if positive), rounded to the nearest $5
- **Artist Total** = Sum of all artist contract rates plus their bonuses
- **Deposit** = Total Cash - Artist Total
- **"Profit"** = Deposit + Zeffy/Electronic - Rent
