---
layout: project
type: project
image: images/bot-status.png
title: Hana Bot
permalink: projects/hana-bot
# All dates must be YYYY-MM-DD format!
date: 2019-06-30
labels:
  - Python
  - MongoDB
  - discord.py
summary: A discord bot made with discord.py (python) and MongoDB.
---
As of 2020-1-19, the project is still ongoing.


Hana bot is a discord bot mainly built for moderation purposes.

Some notable features:
* Basic moderation commands such as prune, kick, ban...
* Converting server updates the bot receives and sends it into the desired channel as embeds
  * <img class = "name change" src = "/images/update1.png">
* Scans message / name update received from a member through given word list for inappropriate words
* Role menu base on user reaction
  * <img class = "color role menu" src = "/images/update2.png">
* Anti raid
* Mute / Warn system
* Automatic join role system
* Interactive (reaction based) help menu
* RPG "mini-game" system (PvP tested working, need to manually add skills. Alpha-test stage.)
* Debug-mode
  * <img class = "error report" src = "/images/help-menu.png">


The source code can be found [here](https://github.com/Necom1/Hana-Bot).
