---
layout: project
type: project
image: images/project/discord-bot/intro.png
title: Discord Bot
permalink: projects/discord-bot
date: 2019-06-30
labels:
  - Python
  - MongoDB
  - Discord.py
  - Personal Project
summary: A moderation Discord bot made with Discord.py and MongoDB. It contains standard moderation commands like prune, kick, and ban; but also have a chat scanner to remove "inappropriate" messages and a raid detection system.
---
As of 2021-6-30, the project have a stable release.

Mango is a discord bot mainly built for moderation purposes. The bot is not server dependent (using MongoDB to store settings), so this can work on any server and multiple servers. However, the first time setup might take some time as settings can only be changed through discord alone.

<img class="big intro" src="/images/project/discord-bot/log.png">

Some notable features:
* Basic moderation commands such as prune, kick, ban...
* Converting server updates the bot receives and sends it into the desired channel as embeds
* Scans message / name update received from a member through given word list for inappropriate words
* Role menu base on user reaction
* Anti raid
* Mute / Warn system
* Reminder system
* Automatic join role system

<div class="ui medium rounded images">
  <img class="ui images" src="/images/project/discord-bot/antiraid.png">
  <img class="ui images" src="/images/project/discord-bot/role.png">
</div>

Through programming Mango Pi, I was able to put all the skills I've learned like recursion, classes, inheritance into practical use and train me how to debug a program. On top of that, I was able to get a good understanding on Python and MongoDB.

The source code can be found [on my other Github account](https://github.com/Necom1/Mango-Pi).
