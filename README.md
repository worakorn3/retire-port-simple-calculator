# Retirement Portfolio Simulator

This project provides a web-based Retirement Portfolio Simulator, designed to help you visualize the potential growth and dividend income of an investment portfolio. It allows for customization of ETF allocations and various simulation parameters.

## Purpose

The simulator is built to demonstrate how different investment strategies and market conditions might impact a retiree's portfolio over time, specifically focusing on capital appreciation and dividend income.

## Features

* **Customizable ETF Allocation:** Adjust the percentage allocation for SCHD, VOO, and SCHG ETFs. The sum of these allocations must be exactly 100%.

* **Flexible Initial Capital:** Define a range for your initial investment by setting a lower capital, a ceiling capital, and the number of steps to simulate within that range.

* **Adjustable Duration:** Set the simulation period in years (1 to 50 years).

* **Expected Annual Growth Rate:** Input your anticipated annual growth rate for the portfolio's capital appreciation. A default value is provided based on the weighted average historical performance of the selected ETFs.

* **Dividend Reinvestment Plan (DRIP) Toggle:** Choose whether dividends are reinvested back into the portfolio (compounding growth) or taken as cash.

* **Separate Results Tables:** View projected portfolio value and cumulative dividends in two distinct tables.

* **Table Pagination:** For longer durations, results are paginated, displaying 10 years per page for easier navigation.

* **Formatted Inputs:** Capital input fields automatically format with comma separators for improved readability.

* **ETF Performance Insights:** A table provides approximate 10-year average capital appreciation, dividend yield, and dividend growth rates for SCHD, VOO, and SCHG.

## How to Use

1. **Save the File:** Copy the entire HTML code provided in the `portfolio_simulator` artifact.

2. **Create an HTML File:** Paste the copied code into a plain text editor (e.g., Notepad, VS Code, Sublime Text).

3. **Save as `.html`:** Save the file with an `.html` extension (e.g., `index.html` or `retirement_simulator.html`).

4. **Open in Browser:** Open the saved HTML file in any modern web browser (Chrome, Firefox, Edge, Safari, etc.).

5. **Adjust Parameters:** Use the input fields under "ETF Allocation Ratios" and "Simulation Parameters" to customize your scenario.

6. **Run Simulation:** Click the "Run Simulation" button to update the results tables.

7. **Navigate Pages:** If your simulation duration is longer than 10 years, use the "Previous 10 Years" and "Next 10 Years" buttons to navigate through the results.

## Disclaimer

**Disclaimer:** This Retirement Portfolio Simulator is provided for **educational and informational purposes only**. It is not intended as, and should not be considered, financial, investment, tax, or legal advice. The results are based on user-defined inputs and approximate historical averages, which do not guarantee future performance. Investing involves risks, including the potential loss of principal. Always consult with a qualified financial professional before making any investment decisions.
