# 🚀 Bot Setup Instructions

Welcome to the bot setup guide! Follow the steps below to install and configure the bot correctly. This guide is designed to be beginner-friendly, with clear explanations for each step.

---

## Table of Contents

1. [Configuration Files](#configuration-files)
   - [`configs.json`](#1-configsjson)
   - [`datas.txt`](#2-datastxt)
   - [`proxies.txt`](#3-proxiestxt)
2. [Running the Bot](#running-the-bot)
3. [Contact and Support](#contact-and-support)

---

## Configuration Files

### 1. `configs.json` - 📜 Adjust Bot Settings

This file controls the bot’s behavior. Below is an example configuration:

```json
{
  "timeZone": "en-US",
  "skipInvalidProxy": false,
  "delayEachAccount": [5, 8],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 100,
  "referralCode": "ABTLFV"
}
```

- **Fields Explained:**
  - `timeZone`: Time zone setting (e.g., "en-US").
  - `skipInvalidProxy`: Skip invalid proxies if `true`.
  - `delayEachAccount`: Random delay range (in seconds) between accounts.
  - `timeToRestartAllAccounts`: Time (in seconds) to restart all accounts.
  - `howManyAccountsRunInOneTime`: Number of accounts to run simultaneously.
  - `referralCode`: Add your referral code (optional). Do not change it if you want to support me ^^

### 2. `datas.txt` - 🗂️ User Data

Fill the `datas.txt` file with your private keys of evm wallets.

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)

```txt
0x...
0x...
0x...
```

_Note: Each row for each account_

### 3. `proxies.txt` - 🌐 Proxy List (Optional)

If you are using proxies, add them here. Leave the file blank if you are not using proxies. Supported formats:

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
http://host:port
https://host:port
socks4://host:port
socks5://host:port
```

_Note: each row for each account_

---

## Running the Bot

1. Navigate to the folder containing the bot files:

   ```bash
   cd /path/to/bot-folder/
   ```

2. Run the bot using the following command:

```bash
./meomundep.exe
```

---

## Contact and Support

- **Help me with your referral** [Referral Link](https://xp.iagentpro.com/?ref=ABTLFV) | [Telegram referral Link](https://t.me/AGNTxpBot/AGNTxp?startapp=rid-1dab9f7e-7b16-4c1b-bf8c-d62ddc212ea2)
- **Buy me a telegram account** [Here](https://t.me/KeoAirDropFreeNe/312/27801) or [Here](https://github.com/MeoMunDep/MeoMunDep)

If you encounter any issues or have questions, feel free to reach out:

- **Contact:** [Contact Me](https://t.me/MeoMunDep)
- **Group:** [Join the Group](https://t.me/KeoAirDropFreeNe)
- **Channel:** [Visit the Channel](https://t.me/KeoAirDropFreeNee)

Your support is greatly appreciated! 🐱

---

Enjoy using the bot! 🚀
