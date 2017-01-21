# reddit-to-telegram

This script will watch the new content on a subreddit and post to a Telegram channel.

## Config

* Create a `praw.ini` file:
```
[default]
client_id: <client id>
client_secret: <client secret>
username: <reddit user name>
password: <reddit user password>
```
* Set the following env vars:
  * `SUBREDDIT` - subreddit name
  * `TOKEN` - Telegram bot token
  * `CHANNEL` - Telegram chat name (the bot has to be added as Administrator)
  
* Run `python3 telegram_poster.py`
