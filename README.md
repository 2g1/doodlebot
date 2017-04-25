# doodle
A helpful bot for Discord that adds a variety of features useful for running a server.

## Features
* Captcha
* Message Snooping
* Reactions (Planned)
* Drawing prompts (Planned)

## Requirements
* Node
* NPM
* Discord.JS
* INI
* CCAP.
Running `depenencies.sh` will automatically install these for you.

## Setting up the bot

After installing, `config/config.ini` should be edited to set up the bot.

First, you will need to create a bot. You can follow this guide to do so:
https://github.com/Just-Some-Bots/MusicBot/wiki/FAQ#how-do-i-create-a-bot-account

The three configuration settings that will need to be changed are `BotID`, `Token`, and `UserID`.

Your `BotID` and `Token` can be found on your bot's application page under the "APP BOT USER" section.
![Help Image](http://i.imgur.com/NO5h19G.png)

`UserID` is **your** Discord user ID. This is needed to give you access to developer-only commands. To find this, enable developer view in your discord options (setting->appearance->developer mode). Afterwards, right click on your name either on a message that you've sent, or on your name in a server's members list, and click `Copy ID`.
(The BotID can also be acquired like this by right clicking on the bot's name instead of your own)

Finally, you can add the bot to a server by following this guide:
https://github.com/Just-Some-Bots/MusicBot/wiki/FAQ#how-do-i-add-my-bot-account-to-a-server


## Optional Things

Optionally, the command prefix can be changed in `config.ini`. (The default is `%`)
