<h1 align= center>Telegram Session Controller Bot</h1>
<h3 align = center>A telegram bot that control user id effortlessly whether its Pyrogram or Telethon (user string only)</h3>
<p align="center">
<a href="https://python.org"><img src="http://forthebadge.com/images/badges/made-with-python.svg" alt="made-with-python"></a>
<br>
    <img src="https://img.shields.io/github/stars/madara1188/DESTROYERS-SESSION-HACK?style=for-the-badge" alt="Stars">
    <img src="https://img.shields.io/github/forks/madara1188/DESTROYERS-SESSION-HACK?style=for-the-badge" alt="Forks">
    <img src="https://img.shields.io/github/watchers/madara1188/DESTROYERS-SESSION-HACK?style=for-the-badge" alt="Watchers"> 
<br>
    <img src="https://img.shields.io/github/repo-size/madara1188/DESTROYERS-SESSION-HACK?style=for-the-badge" alt="Repository Size">
    <img src="https://img.shields.io/github/contributors/madara1188/DESTROYERS-SESSION-HACK?style=for-the-badge" alt="Contributors">
    <img src="https://img.shields.io/github/issues/madara1188/DESTROYERS-SESSION-HACK?style=for-the-badge" alt="Issues">
</p>

## Config Vars

1. `API_ID` : Telegram API_ID, get it from my.telegram.org/apps
2. `API_HASH` : Telegram API_ID, get it from my.telegram.org/apps
3. `BOT_TOKEN` : A valid bot token, get it from [@BotFather](https://t.me/BotFather)
4. `SUDOERS` : Sudo ids (Example: 5805639231 5734659617 )
5. `MONGO_URL` : A Mongo Url for storing user ids, get it from cloud.mongodb.com
6. `LOG_GROUP_ID` : Your channel's or group's Telegram id (Example: -1002025766361)
7. `MUST_JOIN` : Telegram channel(TEAM_DST) for force subs
8. `DISABLED`: Menu names which you want to disable, without space (Example: a b j)

## Deployment Methods

### Vps

To deploy on a VPS, follow these steps

1. Update and upgrade your system packages:

```
sudo apt-get update && sudo apt-get upgrade -y
```

2. Clone the repository and navigate to the project directory:

```
git clone https://github.com/madara1188/DESTROYERS-SESSION-HACK && cd SessionBot
```

3. Install the required packages:

```
pip3 install -U -r requirements.txt
```

4. Create .env using example.env

```
cp example.env .env
```

5. Now open the .env file using **vi .env**
6. Edit the vars, by pressing **I** on the keyboard
7. After editing save the file using **ctrl + c** then **:wq**
8. Run the script using Python 3:

```
python3 -m Hack
```

### HEROKU

[![Deploy on Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/madara1188/DESTROYERS-SESSION-HACK)

## Support

- [Channel](https://t.me/TEAM_DST)
- [Group](https://t.me/TEAM_DST)
- [Heroku by](t.me/CODEX_MADARA)

## Credits

- [Telethon](https://github.com/LonamiWebs/Telethon)
- [Ultroid](https://github.com/TeamUltroid/Ultroid)
- [Heroku Deployer](t.me/CODEX_MADARA)
