# Unlimited Filter Bot


<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg">

  </a>
</p>
<p align="center">
  <a href="https://github.com/Senu-Infinity/Filter-Bot/stargazers">
    <img src="https://img.shields.io/github/stars/Senu-Infinity/Filter-Bot?style=social">

  </a>
  
  <a href="https://github.com/SenuGamerBoy/Senu-Infinity/Filter-Bot/fork">
    <img src="https://img.shields.io/github/forks/Senu-Infinity/Filter-Bot?label=Fork&style=social">

  </a>  
</p>

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FSenu-Infinity%2FFilter-Bot&count_bg=%2379C83D&title_bg=%23555555&icon=mailchimp.svg&icon_color=%23E7E7E7&title=Views&edge_flat=false)](https://hits.seeyoufarm.com)  
ㅤㅤㅤㅤㅤㅤㅤ  
[![Senu Infinity](https://img.shields.io/badge/SenuInfinity-Support-red?style=flat&logo=telegram)](https://telegram.dog/senuinfinitygroup) 
ㅤㅤㅤㅤㅤㅤㅤ  
[![MIT license](https://img.shields.io/badge/License-MIT-blue?style=flat)](https://github.com/Senu-Infinity/Filter-Bot/blob/main/LICENSE)  [![Open Source](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/SenuGamerBoy/Unlimited-Filter-Bot-V1)


## An advanced Filter Bot with nearly unlimitted filters 😎!


### Features
* Nearly unlimited filters ♾
* Supports all type of filters(Including Alert Button Filter). 😏
* Can save button filters directly (Rose Bot Feature) 🌹
* Supports multiple PM connections 💥
* And all other features of a Filter Bot 🔥


#### Deploy the bot and start adding your filters :)


## How to use the bot 🦢
* Add bot to your group with admin rights.

* Add your filters :)


## Bot Commands 💾

(You need to be an admin or Auth User in order to use these commands💖)

> Filter Commands
* `/add <filtername> <filtercontent>`  -  To add your filter. You can also reply to your content with /add command.

* `/del <filtername>`  -  Delete your filter.

* `/delall`  -  Delete all filters from group. (Group Owner Only!)

* `/viewfilters`  -  List all filters in chat.

> Connection Commands
* `/connect groupid`  -  Connects your group to PM. You can also simply use, `/connect` in groups.

* `/connections`  -  Manage your connections. (only in PM)

> Extras
* `/status`  -  Shows current status of your bot (Auth User Only)

* `/id`  -  Shows ID information

* `/info <userid>`  -  Shows User Information. Also use `/info` as reply to some message for their details!


## You can check the video tutorial on how to deploy

[Click here to see tutorial video](coming soon)

## Any bugs or errors or suggestions, report at [Senu Infinity Support](https://telegram.dog/senuinfinitygroup)


## Installation

### Deploy to Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/Senu-Infinity/Filter-Bot/)

### Deploy in your vps
```sh
git clone https://github.com/Senu-Infinity/Filter-Bot/
cd Unlimited-Filter-Bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 bot.py
```


## Configs

* TG_BOT_TOKEN  - Get bot token from @BotFather

* API_ID        - From my.telegram.org (or @UseTGXBot)

* API_HASH      - From my.telegram.org (or @UseTGXBot)

* AUTH_USERS  - ID of users that can use the bot commands. Get from [MissRose Bot](https://telegram.dog/MissRose_bot) by using /id command

* DATABASE_URI  - Mongo Database URL from https://cloud.mongodb.com/

* DATABASE_NAME  - Your database name from mongoDB. Default will be 'Cluster0'

* SAVE_USER  -  Give yes or no . Usefull for getting userinfo and total user counts. May reduce filter capacity :( .

* HEROKU_API_KEY  -  To check dyno status. Go to https://dashboard.heroku.com/account , scroll down and press Reveal API


### Optional - To set alternate Bot Commmands!
( *Add required field as heroku var and give desired command as value. You can edit it in sample_config.py also!*)

* ADD_FILTER_CMD  -  default will be 'add'

* DELETE_FILTER_CMD  -  default will be 'del'

* DELETE_ALL_CMD  -  default will be 'delall'

* CONNECT_COMMAND  -  default will be 'connect'

* DISCONNECT_COMMAND  -  default will be 'disconnect'

EG;  
![Vars Eg](https://telegra.ph/file/1f956f3491f2f20a9c1ec.jpg)
