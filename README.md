# Twitter Bot Sample
A sample Twitter bot in Python

---

## Set up notes

### How to install Tweepy

First, check your Python version with ``python3 --version`` or ``python --version`` on console (terminal/shell/command prompt).

#### If you have Python 3.9, you can just run:

``pip3 install tweepy``

If the above command doesn't work, try replacing ``pip3`` with ``pip`` also.
---

## Files
- **twitter_bot.py** - This is the main file that includes all the logic.
- **last_seen_id.txt** - This will contain the ID of the tweet that my_twitter_bot.py has seen last. If you see any errors when running the main file, try replacing the content with the ID of one of the tweets you want to examine.
- **keys.py** - This file is not meant to be used directly. Instead, copy this file in the same folder and rename it to keys.py. Then, put your Twitter API keys in keys.py. That way, my_twitter_bot.py will be able to use this information.
