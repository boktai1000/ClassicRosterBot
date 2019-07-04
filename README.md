# Classic Roster Bot
### Discord Bot for WoW Classic that can track the total amount of players in a Class as well as total Raiders in a post on your Discord server

## Technical Requirements
- Node.js
- Discord.js (Tested with 11.5.0)
- file-system (NPM module, tested with 2.2.2)

## Discord Requirements
- Server ID
- Channel ID
- The following roles: Raider, DPS, Healer, Tank, Druid, Hunter, Mage, Paladin, Priest, Rogue, Warlock, Warrior

## Usage
- wow-initial.js

This is used to create your initial post, you can continue to use this file but the Bot will continue to periodically post and create new posts. This could be potentially problematic for your server.

- wow-persistent.js

This is used to embed a Message ID into the JS file to hardcode and inform the Bot to only edit and modify that post. This will prevent the bot from creating new posts.

## Heroku
How to host a Node.js bot for free on Heroku
- https://medium.com/@mason.spr/hosting-a-discord-js-bot-for-free-using-heroku-564c3da2d23f
