# Telegram Bot for User Data Management and Payment Processing

This bot is designed to manage user data and process payments. It uses the Telegram API, openpyxl for handling Excel files, the logging module for logging, and stripe for payment processing.

## Features

- **User Data Management**: The bot can check if a user is in an Excel sheet, find the row of a user, and update the data of a user in the sheet.
- **Payment Processing**: The bot can create a stripe checkout session and a payment order.
- **Error Handling**: The bot can send error messages to the chat if a condition is not met.

## Dependencies

- Python 3.6 or higher
- python-telegram-bot
- openpyxl
- logging
- requests
- asyncio
- random
- string
- urllib
- datetime
- stripe

## Setup

1. Clone this repository.
2. Install the dependencies using pip:
3. Replace the placeholders in the code with your actual data. For example, replace `NOWPAYMENTS_API_KEY` with your actual NowPayments API key.
4. Run the bot:


## Usage

After setting up the bot, you can use the following commands in the Telegram chat:

- `/accetta`: Accept the privacy policy and proceed with the registration.

Please note that the bot is currently in Italian. You might need to translate the messages to your preferred language.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
