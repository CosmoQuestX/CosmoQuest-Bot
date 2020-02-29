<img alt="Discord" src="https://img.shields.io/discord/443490369443856384?label=CosmoQuest&logo=Discord&style=social">

# CosmoQuest Bot ![Picture](https://static-cdn.jtvnw.net/jtv_user_pictures/5d474961-8648-4a43-97d5-8dec6f6babd3-profile_image-50x50.png)

Bot developed for the CosmoQuest server on Discord.

## Description:

This robot is made and maintained by the server and Cosmoquest community. 
It was created based on the suggestions of users and volunteer developers of this bot.

## **This bot uses:**

• [Botkit](https://botkit.ai/): A handy bot building framework

• [Discord.js](https://discord.js.org/): A node module for connecting to the Discord API

• [Botkit Discord](https://www.npmjs.com/package/botkit-discord): A connector that allows you to use Bokit and Discord.js

• [Uptime Robot](https://uptimerobot.com/): A monitoring service that helps keep your bot running 24/7

## The Code

**assets**
This is where you can add images, sound files, and other media.

**public/client.js**
This is the interactive code for the setup guide.

**public/install.js**
This is the interactive code for the install guide.

**public/style.css**
This is the styling for the install and setup guides

**skills/hears.js**
This is an Botkit skill for your bot allowing it to respond to certain words it "hears" on the server.

**views/index.html**
This is the basic webpage for the setup guide

**views/install.html**
This is the basic webpage for the install guide

**.env (open, API bot not included)**
This is a file for storing secure info like API keys

**.gitignore**
Git is a "version control" system, which is a fancy way of saying it backs up a record of all your code. This file tells git not to back up certain files. For example we don't want it backing up because it contains secure info..env

**bot.js**
This is the base code initializing the bot by giving it to the Discord Api key and telling it where the skills files are

**guides.js**
This contains the code that makes the guides accessible and interactive

**package.json**
This is a file that contains info about your project, like what node modules it should install

**readme.md**
This is this file! It's full of helpful info.

**server.js**
This contains the code that connects all the different pieces of the bot together so it can be started by package.json
