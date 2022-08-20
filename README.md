# Apex Legends Status Rotation

A discord bot to display the current server status for Apex Legends, updating automatically on a set interval. Requires Node 14 and D.JS 13.

# Setup

Simply clone the repo into a folder, and then run `npm ci` to install all the dependencies. Make a copy of config.json.example and name it config.json.

Run the bot with empty values, find the channel you want the message to post in, then type `!template` (replace '!' with the prefix you set in the config) to set the template message. Then, return to the config and add the message and channel ID's to the config. Restart the bot and it should automatically update.

`npm run dev` runs the dev environment for testing, and `node Rotation.js` will run the bot for production. I suggest something like PM2 if you plan on running the bot on a server.
