# trade_signals
A python project intended to provide the user with trading signals based on a Bull Ride day trading strategy
# Stock Signal Generator

## Overview
This application monitors selected stocks and generates buy/sell signals based on technical indicators. It uses the Alpaca API for market data and MongoDB for storing signals.

## Features
- Real-time stock monitoring
- Technical analysis using MACD, VWAP, and RSI
- Customizable stock selection
- MongoDB integration for signal storage
- Desktop notifications for buy/sell signals

## Prerequisites
- Python 3.7+
- Alpaca API account
- MongoDB account

## Installation
1. Clone the repository:https://github.com/flowersandscumbags/trade_signals/
git clone https://github.com/flowersandscumbags/trade_signals/.git
cd stock-signal-generator
2. Install dependencies:
pip install -r requirements.txt
Copy
3. Set up environment variables:
Create a `.env` file in the project root with the following:
ALPACA_API_KEY=your_alpaca_api_key
ALPACA_SECRET_KEY=your_alpaca_secret_key
MONGODB_URI=your_mongodb_connection_string
Copy
## Usage
Run the script:
python main.py
CopyFollow the prompts to select stocks for monitoring.

## Configuration
- Modify `DEFAULT_SYMBOLS` in the script to change the default stock list.
- Adjust technical indicator parameters in the `generate_signal` function as needed.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
[MIT License](LICENSE)

## Disclaimer
This software is for educational purposes only. Do not use it for actual trading without understanding the risks involved.
