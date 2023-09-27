# Telegram Listing Bot for TradingView

![Bot Logo](bot_logo.png) 

## Overview

The Telegram Listing Bot for TradingView is a tool designed to automate the process of sending trading signals and alerts from the TradingView platform to a Telegram channel or group. This bot enables traders and analysts to share market insights, technical analysis, and trading signals with their Telegram community seamlessly.

### Features

- Automated integration with TradingView alerts.
- Real-time delivery of trading signals to a Telegram channel or group.
- Customizable alert filtering and formatting options.
- Support for multiple Telegram channels and groups.
- Easy-to-use configuration and setup.

## Installation

Follow these steps to set up and run the Telegram Listing Bot for TradingView on your server:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/rekt-lord/tradingView-telegram-bot.git
   cd tradingView-telegram-bot

2. Configure your environment:
Create a `.env file` in the project's root directory and define your environment variables. You can use the `.env.example` file as a template.
3. Start the bot.

## Usage
1.Setup Telegram Integration:
Configure your bot on Telegram and obtain the API token and chat ID.
2.Configure TradingView Alerts:
Set up alerts on TradingView for the assets and conditions you want to monitor.
3.Bot Configuration:
Customize the bot's behavior by editing the configuration options in the .env file.
4.Run the Bot:
Start the bot using npm start to begin listening for TradingView alerts and sending them to your Telegram channel or group.
