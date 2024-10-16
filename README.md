Reddit Comment Bot
This Reddit Comment Bot is a Python-based auto-responder.

Pick a subreddit to scan.
Designate a specific comment to search for.
Set your bot's reply.
Requirements
Python
Praw
A Reddit Account
Setup
Reddit App:

Navigate to the Apps page
Click create an app
name: Set a name for your app
type: Script
description: Optional
about url: Optional
redirect uri: http://localhost:8080
Note the outputted client id and secret
config.py:

REDDIT_USERNAME: your Reddit username
REDDIT_PASSWORD: your Reddit password
REDDIT_CLIENT_ID: the outputted client id
REDDIT_CLIENT_SECRET: the outputted secret
REDDIT_USER_AGENT: a unique identifier for your bot
TARGET_SUBREDDIT: the subreddit to scan (default = "test")
TARGET_STRING: the comment search criteria (default = "sample user comment")
REPLY_MESSAGE: your bot's comment reply (default = "Hey, I like your comment!")
SLEEP_DURATION: sleep duration between bot runs in seconds (default = 10)
Usage
Navigate into the bot directory.
Run your bot:
