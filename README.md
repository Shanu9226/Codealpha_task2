Stock Portfolio Tracker
A simple Python application that allows you to track the value of stocks in your portfolio using live data from Yahoo Finance.

Description
This application helps you manage and track the value of your stock portfolio. It fetches real-time stock prices using the Yahoo Finance API (yfinance library) and calculates the value of your portfolio based on the current prices.

Features
Track stock symbols and quantities in your portfolio.
Fetch live stock prices from Yahoo Finance.
Calculate the current value of your portfolio based on stock prices.
Display detailed information about each stock and the total portfolio value.
Requirements
Python 3.x
yfinance library
Installation
Clone this repository:

bash
Copy
git clone https://github.com/yourusername/stock-portfolio-tracker.git
Navigate to the project directory:

bash
Copy
cd stock-portfolio-tracker
Install the required dependencies:

bash
Copy
pip install yfinance
Ensure that Python 3 is installed by checking the version:

bash
Copy
python --version
Usage
Open the portfolio_tracker.py file and add stocks to your portfolio using the add_stock() method.

To track live stock prices and display your portfolio value, simply run the Python script.

bash
Copy
python portfolio_tracker.py
The portfolio will be updated with the latest stock prices and display the total value of the portfolio.

Example Output
yaml
Copy
AAPL: 10 shares at 150.00 each, value: 1500.00
TSLA: 5 shares at 900.00 each, value: 4500.00
GOOG: 2 shares at 2700.00 each, value: 5400.00
Total Portfolio Value: 11400.00
Code Overview
Stock Class:

Represents a stock with a symbol and quantity.
Retrieves the current stock price using the Yahoo Finance API.
Calculates the value of the stock in the portfolio.
Portfolio Class:

Holds multiple stocks.
Allows you to add new stocks to the portfolio.
Updates the prices of all stocks.
Displays the details of each stock and the total portfolio value.
Contributing
Fork this repository.
Create a new branch (git checkout -b feature-name).
Make your changes.
Commit your changes (git commit -am 'Add feature').
Push to the branch (git push origin feature-name).
Create a Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
