# Classic Roster Bot
### A way to track total raiders as well as number of each class for your Guild via a Discord Bot

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
