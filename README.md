
---

# 🚀 Bitcoin Transaction Fee Alert Discord Bot

This is a Discord bot that connects to the Bitcoin Mempool API (mempool.space) to monitor current transaction fees and notify users when their desired target fee (specified in USD) is reached. Users can receive notifications via tagged messages in a specific channel.

## Features

- 📈 Fetches current Bitcoin transaction fees from the Mempool API.
- 💵 Allows users to set target fees in USD.
- 🔔 Notifies users when the current fastest fee is below their target fee.
- 📬 Sends notifications by tagging users in a specific channel.

## Getting Started

### Adding the Bot to Your Server

1. **Invite the bot to your server**: Use the following link to add the bot to your Discord server. Ensure you have the necessary permissions to add bots.
   
   [Invite Link](https://discord.com/oauth2/authorize?client_id=1244394848036061325&permissions=8&scope=bot)

2. **Authorize the bot**: Follow the instructions to authorize the bot and grant it the required permissions.

### Commands

- `!fee`: Fetches and displays the current transaction fees.
- `!setfee <target_fee_in_usd>`: Sets a target fee in USD for the user. The bot will notify the user when the current fastest fee is below this target.

### Example Usage

- `!fee`:
  ```
  📊 Current fees:
  🚀 Fastest Fee: 14 sat/vB ($ 2.43/vB)
  🕐 Half Hour Fee: 12 sat/vB ($ 2.08/vB)
  ⏳ Hour Fee: 10 sat/vB ($ 1.73/vB)
  ```

- `!setfee 2.50`:
  ```
  ✅ Set target fee to 2.50 USD (0.01 sat/vB) for @user.
  ```

## License

Not specified yet, as it is closed-source.

## Acknowledgements

- 🤖 [discord.py](https://github.com/Rapptz/discord.py) - Python wrapper for the Discord API
- 📡 [Mempool.space API](https://mempool.space/api) - Bitcoin Mempool API for transaction fee data
- 💱 [CoinDesk API](https://www.coindesk.com/coindesk-api) - Bitcoin price index API

---
