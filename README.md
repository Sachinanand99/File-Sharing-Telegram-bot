# File-sharing-Bot

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg" width ="250">
  </a>
</p>


Telegram Bot to store Posts and Documents and it can Access by Special Links.
I Guess This Will Be Usefull For Many People.....😇. 

### Features
- Fully customisable.
- Customisable welcome
- More than one Posts in One Link.
- Can be deployed on heroku directly.

### Setup
- Add the bot to Database Channel with all permission

### Installation
#### Deploy on Heroku
**BEFORE YOU DEPLOY ON HEROKU, YOU SHOULD FORK THE REPO AND CHANGE ITS NAME TO ANYTHING ELSE**<br>
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)</br>
<a href="https://youtu.be/LCrkRTMkmzE">
  <img src="https://img.shields.io/badge/How%20to-Deploy-red?logo=youtube" width="147">
</a><br>
**Check This Tutorial Video on YouTube for any Help**<br>
**Thanks to [Erich](https://t.me/ErichDaniken) and his [InFoTel](https://t.me/InFoTel_Group) for this Video**

#### Deploy on Railway
[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/1jKLr4)

#### Deploy on Koyeb

The fastest way to deploy the application is to click the **Deploy to Koyeb** button below.


[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/CodeXBotz/File-Sharing-Bot&branch=koyeb&name=filesharingbot)


#### Deploy in your VPS
````bash
git clone https://github.com/Sachinanand99/File-Sharing-Bot.git
cd File-Sharing-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
````

## Basic Commands
- `/start` - Check whether bot is online 🟢
- `/stats` - Uptime of the bot (admin only) ⏱️
- `/users` - Total users active (admin only) 👥
- `/batch` - To generate the link in batch (admin only) 🔗
- `/genlink` - To generate link (admin only) 🔀
- `/auth` - For using the bot which will send the ID to the owner's DM. The owner will add the admin to config file and restart the bot.

## Secret Commands
- `/broadcast` - Reply to any message to broadcast it to all users(owner only).
- `/auth_secret <id>` - (for owner only) when the user is verified for admin and owner restarts the bot, this command will send the user of which the id is written will get a message to join the channel from where he/she can forward message for using the batch command.


### Variables

* `API_HASH` Your API Hash from my.telegram.org
* `APP_ID` Your API ID from my.telegram.org
* `TG_BOT_TOKEN` Your bot token from @BotFather
* `OWNER_ID` Must enter Your Telegram Id
* `CHANNEL_ID` Your Channel ID eg:- -100xxxxxxxx
* `DATABASE_URL` Your mongo db url
* `DATABASE_NAME` Your mongo db session name
* `TIME` Time in seconds for message to get delete after downloading file
* `ADMINS` Optional: A space separated list of user_ids of Admins, they can only create links
* `START_MESSAGE` Optional: start message of bot, use HTML
* `FORCE_SUB_MESSAGE`Optional:Force sub message of bot, use HTML and Fillings
* `FORCE_SUB_CHANNEL` Optional: ForceSub Channel ID, leave 0 if you want disable force sub
* `FORCE_SUB_CHANNEL2` Optional: ForceSub Channel ID, leave 0 if you want disable force sub 2, bot may become a bit slower if you add this.
* `PROTECT_CONTENT` Optional: True if you need to prevent files from forwarding


### Token verification variables

* `SHORTLINK_URL` Your Shortner url. eg: shareus.io
* `SHORTLINK_API` shortner api key.
* `VERIFY_EXPIRE` verify expire time in seconds.
* `IS_VERIFY` Verify True Or False.
* `TUT_VID` Verification tutorial video link


### Extra Variables

* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False
* `BOT_STATS_TEXT` put your custom text for stats command, use HTML
* `USER_REPLY_TEXT` put your text to show when user sends any message, use HTML


### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption

#### CUSTOM_STATS

* `{uptime}` - Bot Uptime


Report Bugs, Give Feature Requests There..   

### Credits

- Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)

##

   **Star this Repo if you Liked it ⭐⭐⭐**

