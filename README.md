# Fujao Bot for Telegram
Under development......

## Introduction
This is a [Telegram](https://telegram.org/) bot sending fujao-time sentences telling time every hour. You can start or stop any time using commands.

Modified from [imxieyi/sticker_time_bot](https://github.com/imxieyi/sticker_time_bot)

## Commands
**Start sending sentences:** `/start`

**Stop sending sentences:** `/stop`

**Set timezone:** `/timezone Asia/Shanghai`

*List of timezones in tz database: [https://en.wikipedia.org/wiki/List_of_tz_database_time_zones](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones)*

**Enable/Disable auto deleting messages:** `/autodelete [on|off]`

**Set sleep time:** `/sleeptime [0-23]`

**Set wake time:** `/waketime [0-23]`

## Environment
- Node.js 8.0+

## Installation
```sh
npm install
```

## Configuration
Create a file config.json:
```json
{
    "tg_bot_token": "Your Telegram bot token here",
    "log_file": "Log file"
}
```

## Start
```sh
npm start
```

## License
[SATA / based on MIT](COPYING.md)

Also, thanks to the original developers!