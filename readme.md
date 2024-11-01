# stats-bot
This script hosts a discord bot to get data from the host for https://github.com/Luxxy-GF/Linux-Stats and display the stats

## Getting Started
These instructions will get the script up and running 

### Clone the repo,
```
git clone https://github.com/MasterCatPL/discord-idrac-bot.git 
```

### Installing requirements 
```
npm i
```
This will install all needed packages

### Setting up config.json
copy the .env.template to .env and fill in the bot token from https://discord.dev and the password you set for your https://github.com/Luxxy-GF/Linux-Stats config

also change the ip to your host ip

### Starting the bot 
to start the bot you need a command from nodejs
```
node . or pm2 start index.js (if you installed pm2)
```
this should start the bot