# TG-tondao

🔗 **Referral Link**: [TONxDAO](https://t.me/tonxdao_bot?start=ref_1719410244)

[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/shadowscripters)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ShadowScripts1)

## Table of Contents
- [Warning](#warning)
- [Available Features](#available-features)
- [Registration](#registration)
- [How to Use](#how-to-use)
  - [Windows](#windows)
  - [Linux](#linux)
  - [Termux](#termux)
- [Viewing Reports](#viewing-reports)
- [Support](#support)

## Warning

All risks are borne by the user.

## Available Features

- [x] Automatic claim every 8 hours
- [x] Daily check-in
- [x] Referral result claims
- [x] Proxy support
- [x] Task automation
- [x] Game play after claiming
- [x] Balance reporting for all accounts
- [x] Waiting time before program start
- [x] Auto claim referral rewards
- [x] Auto tap

## Registration

Register via this link: [TONxDAO](https://t.me/tonxdao_bot?start=ref_1719410244)

## How to Use

### Windows

1. Install [Python 3.8+](https://python.org) and [Git](https://git-scm.com/).
2. Clone the repository:
   ```shell
   git clone https://github.com/ShadowScripts1/TG-tondao
   ```
3. Enter the folder:
   ```shell
   cd TG-tondao
   ```
4. Install the requirements:
   ```shell
   python -m pip install -r requirements.txt
   ```
5. Edit `data.txt` with your query data (one line per account).
6. Run the script:
   ```shell
   python bot.py
   ```

### Linux

1. Install Python and Git:
   ```shell
   sudo apt install python3 python3-pip git
   ```
2. Clone the repository:
   ```shell
   git clone https://github.com/ShadowScripts1/TG-tondao
   ```
3. Enter the folder:
   ```shell
   cd TG-tondao
   ```
4. Install requirements:
   ```shell
   python3 -m pip install -r requirements.txt
   ```
5. Edit `data.txt` with your query data (one line per account).
6. Run the script:
   ```shell
   python3 bot.py
   ```

### Termux

1. Install Python and Git:
   ```shell
   pkg install python3 git
   ```
2. Clone the repository:
   ```shell
   git clone https://github.com/ShadowScripts1/TG-tondao
   ```
3. Enter the folder:
   ```shell
   cd TG-tondao
   ```
4. Install requirements:
   ```shell
   python -m pip install -r requirements.txt
   ```
5. Edit `data.txt` with your query data (one line per account).
6. Run the script:
   ```shell
   python bot.py
   ```

## Viewing Reports

To view a total balance report, run:
```shell
python report.py
```

## How to Get `tgWebAppData` (query_id / user_id)

1. Login to Telegram via web or desktop.
2. Open the bot, press `F12`, and go to the Console tab.
3. Run:
   ```javascript
   copy(Telegram.WebApp.initData)
   ```
4. Copy the output (`query_id=... / user=...`) to `data.txt`.

## ⚠️ Notes

- Authentication data is found in the Application tab in DevTools.
- Enable auto features in `config.json` by setting `"false"` to `"true"`.
- Supported commands: `/run_bot`, `/query_id`, `/proxy`, `/proxy_web`.

## 💱 Support

Consider supporting the project:

- EVM: `0x7BeE9994a631523e22A3aB83039c196bFc6BC513`
- SOLANA: `6mbFy6AojWo3J5ksa1SYHHyCWw5Bms4p9McKmaFkCsyW`

## Run File

| With Proxy       | Without Proxy      |
| ---------------- | ------------------ |
| Not supported    | `bot.py` `data.txt` |