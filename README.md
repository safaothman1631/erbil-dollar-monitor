# Erbil Dollar Rate Monitor 💵🤖

Automated monitoring system for the Erbil USD/IQD exchange rate using GitHub Actions and a Telegram bot.

## How it works
1. Runs every hour via **GitHub Actions** in the cloud.
2. Checks public updates from `@azura_gold` on Telegram.
3. Automatically filters and extracts the latest Erbil dollar exchange rate.
4. When a new rate is detected, sends an instant alert to the user's Telegram via `vertex_ads_bot`.
5. Updates and preserves the last state across workflow runs.

## Secrets configured
- `TELEGRAM_BOT_TOKEN`: Telegram bot token from @BotFather
- `TELEGRAM_CHAT_ID`: Telegram recipient user/channel ID
