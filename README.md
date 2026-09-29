# Stabilizer Phase 2 Auto Swap Bot

<img width="1280" height="520" alt="image" src="https://github.com/user-attachments/assets/41bafe70-4766-4818-8ce5-d55a2d664514" />

An automated swap bot for **Stabilizer Phase 2** on **Arbitrum Sepolia**.

The bot automatically performs token swaps between supported stablecoins with multi account randomized amounts and randomized time intervals, allowing you to run swaps continuously without manually making every transaction.

## Features
* 👥 Support multi account
* 🔄 Automatic token swaps
* 🎲 Random token pairs
* 💰 Random swap amounts
* ⏱️ Random delay between swaps
* 📅 Random daily swap target
* 🔐 Automatic token approval
* ⛽ Automatic gas estimation
* 🌐 Arbitrum Sepolia network verification
* 💼 Automatic wallet balance checking
* 🔁 Runs continuously
* 🛑 Automatically stops swapping after reaching the daily target

## Supported Tokens

The bot currently supports:

* USDZ
* USDS
* USDT0
* USDC

The bot randomly selects two different tokens for each swap.

Example:

```text
USDZ → USDC
USDC → USDS
USDT0 → USDZ
USDS → USDT0
```

# Installation

Clone the repository:

```bash
git clone https://github.com/TINGLISE/Auto-Swap-Bot-Stabilizer-Phase-2.git
```

Enter the project directory:

```bash
cd Auto-Swap-Bot-Stabilizer-Phase-2
```

Install dependencies:

```bash
npm install
```

Configuration .env

```bash
nano .env
```

```bash
RPC_URL=https://sepolia-rollup.arbitrum.io/rpc

PRIVATE_KEYS=PRIVATE_KEY_ACCOUNT_1,PRIVATE_KEY_ACCOUNT_2,PRIVATE_KEY_ACCOUNT_3

MIN_DAILY_SWAPS=7
MAX_DAILY_SWAPS=14
MIN_SWAP_AMOUNT=10
MAX_SWAP_AMOUNT=20
MIN_DELAY_MINUTES=30
MAX_DELAY_MINUTES=180
MIN_AMOUNT_OUT=0
```

Start the Bot

```bash
npm start
```

## ⭐ Support

If this bot is useful to you, consider giving the repository a ⭐ on GitHub.

Good luck with your Stabilizer Phase 2 farming!
