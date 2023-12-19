# NewsBot
🤖 Daily News Bot: A Telegram bot that fetches and sends the latest technology news every day at 6:35 AM using GitHub Actions.

## Overview

Daily News Bot is a Telegram bot that delivers the latest technology news to users every day. It utilizes the News API to fetch top headlines in the technology category and sends them to a specified Telegram chat.

## Table of Contents

- [Features](#features)
- [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [GitHub Actions Workflow](#github-actions-workflow)
- [Contributing](#contributing)

## Features

- Fetches the latest technology news from the News API.
- Sends news updates to a specified Telegram chat.
- GitHub Actions workflow for automated daily execution.

## Setup

### Prerequisites

- Python 3.x
- Telegram bot token (obtained from BotFather)
- News API key (obtained from [News API](https://newsapi.org/))

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```

2. Change into the project directory:
```bash
cd your-repository-name
```

3. Create a virtual environment:
```bash
python -m venv venv
```

4. Activate the virtual environment:
```bash
source venv/bin/activate  
```

5. Install dependencies:
```bash
pip install -r requirements.txt
```

6. Create a `.env` file in the project root and add the following:
```bash
YOUR_BOT_TOKEN=your-telegram-bot-token
YOUR_API_KEY=your-news-api-key
TARGET_CHAT_ID=your-telegram-chat-id
```
Replace placeholders with your actual tokens and chat ID.

## Usage

Run the Telegram bot script:
```bash
python scripts/telegram_bot.py

```
The bot will fetch and send the latest technology news to the specified Telegram chat.

## GitHub Actions Workflow
The project includes a GitHub Actions workflow that automatically runs the Telegram bot every day at 6:35 AM IST. The workflow is triggered by a schedule and can also be manually triggered.

## Contributing

Contributions are welcome! If you have suggestions or find issues, please open an issue or submit a pull request.