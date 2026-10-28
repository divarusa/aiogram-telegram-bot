# Telegram Bot with aiogram

A modular Python Telegram bot built with the aiogram framework, featuring a Finite State Machine (FSM) and SQLite integration.

## Features

- FSM (Finite State Machine): state management for step-by-step user interactions
- Modular architecture: command handlers organized in a dedicated directory
- Database integration: SQLite for persistent data storage and custom SQL queries
- Configuration management: centralized environment and bot settings

## Tech Stack

- Python 3
- aiogram
- SQLite3

## Project Structure

- main.py — bot entry point
- config.py — bot settings and environment variables
- handlers/ — command and message handlers
- db/ — database logic

## Getting Started

1. Clone the repository:
git clone https://github.com/divarusa/aiogram-telegram-bot.git
cd aiogram-telegram-bot2. Create a virtual environment and install dependencies:
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt3. Create a .env file in the project root:
BOT_TOKEN=your-bot-token4. Run the bot:
python main.py
