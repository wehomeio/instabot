# Instabot

Free Instagram python bot, [private Instagram API emulator](https://github.com/instagrambot/instabot/tree/master/instabot/api) and a [huge amount of ready-to-use example scripts](https://github.com/instagrambot/instabot/tree/master/examples).

We are the most used Instagram library on GitHub (according to "Used by" counter). 🎉 Join our [Large Telegram community](https://t.me/instabotproject) for more Instagram tricks. 🚀


### Important

Right now the usage of this library (as probably others too) may harm your Instagram's profile because of new script-detection algorithms. You were warned.

---
### [Read the Docs](https://instagrambot.github.io/docs/) | [Contribute](https://github.com/instagrambot/docs/blob/master/CONTRIBUTING.md)
---

[![Telegram Chat](https://img.shields.io/badge/chat%20on-Telegram-blue.svg)](https://t.me/instabotproject)
[![paypal](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://paypal.me/okhlopkov/10)
![Python 2.7, 3.5, 3.6, 3.7](https://img.shields.io/badge/python-2.7%2C%203.5%2C%203.6%2C%203.7-blue.svg)
[![PyPI version](https://badge.fury.io/py/instabot.svg)](https://badge.fury.io/py/instabot)
[![Build Status](https://travis-ci.org/instagrambot/instabot.svg?branch=master)](https://travis-ci.org/instagrambot/instabot)
[![codecov](https://codecov.io/gh/instagrambot/instabot/branch/master/graph/badge.svg)](https://codecov.io/gh/instagrambot/instabot)

### Installation
Install `instabot` with:
``` bash
pip install dist/instabot-0.117.0-py2-none-any.whl
```

#### or check [this](https://instagrambot.github.io/docs/en/#installation) for more details.

### Quickstart

#### How to upload photo with tagged user?
```angular2html
import instabot

bot = instabot.Bot()
bot.login(username="xxx",password="xxx")

pic_path = "media/pict.jpg"
user_tags = [{'user_id': USER_ID, 'x': 0.5, 'y': 0.5}]
caption = "some caption"

bot.upload_photo(pic_path,caption=caption,user_tags=user_tags)
```

#### How to change password?
```angular2html
bot.api.change_password("xxx")
```
How to intercept package traffic?  [look here](https://github.com/aliforever/charles-proxy-instagram-requests)

# Terms and conditions
* You will NOT use this API for marketing purposes (spam, botting, harassment, massive bulk messaging...).
* We do NOT give support to anyone who wants to use this API to send spam or commit other crimes.
* We reserve the right to block any user of this repository that does not meet these conditions.

# Legal
This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by Instagram, Facebook inc. or any of its affiliates or subsidiaries. This is an independent and unofficial API. Use it at your own risk.
