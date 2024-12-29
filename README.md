# Bitpanda Transaction Explorer

A local proxy server and web application for exploring your Bitpanda transactions with enhanced filtering and export capabilities.

## Features

- 🔄 Real-time transaction fetching from Bitpanda API
- 🔍 Transaction filtering
- 📊 Transaction statistics
- 💾 CSV Export functionality for transaction data

## Prerequisites

- Python 3.8 or higher
- Poetry (Python package manager)

## Installation

1. Clone the repository
2. Install dependencies using Poetry:
   ```bash
   poetry install
   ```
3. Run the application:
   ```bash
   poetry run python proxy-server.py
   ```
4. Open `bitpanda-webapp.html` in your browser.
5. Create a new API key (https://web.bitpanda.com/my-account/apikey) in Bitpanda with the `Transaction` and `Balance` permissions. Paste the API key into the input field.
6. Click "Fetch Transactions" to load your transactions.

## Acknowledgments

Built about 90% of the code with Claude 3.5 Sonnet.