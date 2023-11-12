# Kbot - Telegram Bot

Bot example: https://t.me/syriny_kbot 

This Telegram bot is written in Go. To start the bot, follow the instructions below:

## Prerequisites

Before starting the bot, ensure you have the following:

- Go installed on your machine
- Telegram Bot Token (you will need to set it as an environment variable)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/syriny/kbot
    ```

2. Navigate to the project directory:

    ```bash
    cd kbot
    ```

3. Set the TELE_TOKEN environment variable with your Telegram Bot Token:

    ```bash
    export TELE_TOKEN=your-telegram-bot-token
    ```

    Replace `your-telegram-bot-token` with the actual token you obtained from the Telegram BotFather.

4. Build the project:

    ```bash
    go build
    ```

5. Start the bot:

    ```bash
    ./kbot start
    ```

    This command will launch the Telegram bot.

## Notes

- Make sure to keep your Telegram Bot Token confidential and do not share it with anyone.
- Customize the bot's functionality according to your needs by modifying the Go code in the project.
