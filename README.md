# Mempool Fees Discord Bot

A Discord bot to fetch and notify users about current Bitcoin transaction fees.

## Features

- Fetch current Bitcoin transaction fees
- Set a target fee in USD and get notified when the fastest fee is below the target

## Commands

### /fee

Get the current Bitcoin transaction fees.

**Usage:**
```
/fee
```

**Description:**
Fetches the current Bitcoin transaction fees and displays them in the chat.

### /setfee

Set a target fee in USD and get notified when the fastest fee is below the target.

**Usage:**
```
/setfee target_fee_usd: <amount>
```

**Parameters:**
- `target_fee_usd` (required): The target fee in USD.

**Example:**
```
/setfee target_fee_usd: 10.00
```

**Description:**
Sets a target fee in USD. The bot will notify you via direct message when the fastest fee is below the specified target.

## Installation

To add the Mempool Fees Discord Bot to your server, click on the link below and follow the instructions:

[Invite Mempool Fees Bot to your server](https://discord.com/oauth2/authorize?client_id=1244394848036061325&scope=bot+identify+guilds&permissions=2147483647)

### Step-by-Step Guide

1. **Click the Invite Link**: Click on the [invite link](https://discord.com/oauth2/authorize?client_id=1244394848036061325&scope=bot+identify+guilds&permissions=2147483647) to begin the process.

2. **Select a Server**: You will be redirected to a Discord page. Select the server where you want to add the bot from the drop-down menu. Ensure you have the necessary permissions to add bots to the server.

3. **Authorize the Bot**: Click on the "Authorize" button. You may need to complete a CAPTCHA to prove you are not a bot.

4. **Set Up Permissions**: The bot will request permissions to perform its functions. Make sure to grant all requested permissions to ensure it works correctly.

## How It Works

1. **/fee Command:**
   - Fetches the current Bitcoin transaction fees from the Mempool API.
   - Displays the fees in sat/vB and USD based on the current BTC to USD exchange rate.

2. **/setfee Command:**
   - Sets a target fee in USD for the user.
   - Periodically checks the current fastest fee.
   - Notifies the user via direct message when the fastest fee is below the target.

## Support

For support, please open a discussion in the [repository discussions](https://github.com/figueiredofrs/Mempool-Fees-Discord-Bot/discussions).

## License

This project is licensed under the MIT License.
