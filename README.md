# Discord.py Music Bot

A simple music bot written in discord.py using youtube-dl. Use this as an example or a base for your own bot and extend it as you want.

Adapted from this [gist](https://gist.github.com/vbe0201/ade9b80f2d3b64643d854938d40a0a2d), Copyright (c) 2019 Valentin B.

## Pre-Setup

If you don't already have a discord bot, click [Discord Developer Portal](https://discordapp.com/developers/), accept any prompts then click "New Application" at the top right of the screen.  Enter the name of your bot then click accept.  Click on Bot from the panel from the left, then click "Add Bot."  When the prompt appears, click "Yes, do it!"
![Left panel](https://i.imgur.com/hECJYWK.png)

Then, click copy under token to get your bot's token. Your bot's icon can also be changed by uploading an image.

![Bot token area](https://i.imgur.com/da0ktMC.png)

### Setup

Under the "Secret (environment variables)" panel, create a secret
with the key of `TOKEN` and the value from the discord developer bot
page after you click "Reset Token". Click "Add new secret".

### Deploy

To keep your bot alive, simply deploy it on a Reserved VM as a Background Worker by clicking "Deploy" in the top-right corner of the workspace.
