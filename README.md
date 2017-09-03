# selfbot.py

#### *Moderation, fun, utility and much more!*
<img src='https://img.shields.io/badge/build-passing-brightgreen.svg'> [<img src="https://img.shields.io/badge/discord-py-orange.svg">](https://github.com/Rapptz/discord.py) [<img src='https://img.shields.io/badge/python-3.5-brightgreen.svg'>](https://python.org)


[<img src="https://discordapp.com/api/guilds/345787308282478592/widget.png?style=banner2">](https://discord.gg/pmQSbAd) 


## [Installation](https://github.com/verixx/selfbot/wiki)
There are two ways of using the bot, one way is to download it and install it on your computer, the other is to host for free 24/7 on a service called **Heroku**. No download is required, everything is done online. Read the installation guide [here](https://github.com/verixx/selfbot/wiki/Heroku). Its possible to install the selfbot using your phone and it has been done before. If you have any questions, join the support discord server and we will be happy to help.

You need the following to run the bot: This can be done by `pip install -r /path/to/requirements.txt`
```py
discord.py
requests
PythonGists
bs4
lxml
Pillow
mtranslate
```
## Setup
First navigate into the data folder and open `config.json`, edit it to put your token and prefix in. And set `FIRST` to `false`
```json
{
    "FIRST": false,
    "BOT": {
        "PREFIX": "s.",
        "TOKEN": "token_here"
    }
}
```
Alternatively, you could open a terminal in the directory of the bots location and type
```
$ python3 bot.py
```
On first start the launcher will run and you will need to input data. After that the bot will launch without setup neccessary.

## Features

The default set of modules includes:
* Moderation commands
* Global emoji commands
* Complex embed commands
* Custom formatted paginated help
* Miscellaneous commands
* Easy to make your own commands
* Stateless selfbot (Saves no data) *This means that you can [host it on heroku](https://github.com/verixx/selfbot/wiki/Heroku) 24/7 for free*  

These are the [default commands](https://github.com/verixx/selfbot/wiki/Default-Commands)
## Contributors

> [@kwugfighter](https://github.com/kwugfighter)

> [@FloatCobra](https://github.com/FloatCobra)

> [@umbresp](https://github.com/umbresp)

> [@fourjr](https://github.com/fourjr)
