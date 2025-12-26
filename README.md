# FaucetPay USDT Withdraw Backend

Node.js backend for handling FaucetPay USDT withdrawals from a Telegram bot (TeleBotHost).

## Features
- Accepts withdraw requests via POST
- Calls FaucetPay API to send USDT
- Returns success/error to the bot
- API key is stored securely via environment variable

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/faucetpay-usdt-server.git
cd faucetpay-usdt-server
