## Welcome to Mineboty

You can use the [Mineboty](https://github.com/Team-IC/mineboty) to make server 24/7 also you can do pvp practice also.

## Must have node.js version 14 or greater

## step 1
paste this in main start up file
```js
//It can be use also in TypeScript same which is
 const {mineboty} = require("mineboty")
 //no change in main file :)
 mineboty(); 
 //This much only now make config.json
```
##step 2
Must paste in config.json
```json
{
 "ip": "Your_minecraft_server_ip_here",
 "port": "Your_server_port_here",
 "name": "Your_bot_name_here",
 "auto-night-skip": "false",
 "loginmsg": "Your_Login_message_here",
 "prefix": "!",
 "version": "1.17.1"
}
```

## If you are using replit then replace index.js to get the link
```yaml
const express = require("express");

const app = express()

app.get('/', (req, res) => {

  res.send("Use this link for uptime")

})

app.listen(3000, () => {

  console.log("bot started")

})

const { mineboty } = require("mineboty")

mineboty(); 
```

# why mineboty
- mineboty is better than afk bots
- mineboty has multiple features
- easy to use
- helping bot
- Developed by Team-IC 
- login system (so you can also use login so bot dose not get kicked by login plugin)
- prefix
- custom commands 
- and more!!!!
## Happy New Year

# pls help us by staring or forking this repo 
