<h1 align="center">
  VJ FILE STORE BOT
</h1>


![TGFileStore](https://telegra.ph/file/d651c7b7943a9702f846d.png)

⍟ <b>𝗧𝗵𝗶𝘀 𝗶𝘀 𝗧𝗲𝗹𝗲𝗴𝗿𝗮𝗺 𝗣𝗮𝗿𝗺𝗮𝗻𝗲𝗻𝘁 𝗙𝗶𝗹𝗲𝘀 𝗦𝘁𝗼𝗿𝗲 𝗕𝗼𝘁 𝗯𝘆 .<b>

* **Language:** [Python3](https://www.python.org)
* **Library:** [Pyrogram](https://docs.pyrogram.org)

### Features:
- In PM Just Forward or Send any file it will save on Database & give you the Access Link.
- In Channel Add Bot as Admin with Edit Rights. When you will send any file or media in Channel it will Edit the Broadcast Message with Saved Link Button.
- You can also Broadcast anythings via this Bot.
- You can also Do Force Sub to a Channel to allow access the Bot.

### Deploy On Koyeb
<details><summary>Deploy To Koyeb</summary>
<br>
<a target="_blank" href="https://app.koyeb.com/deploy?type=git&repository=github.com/chaley-123/File-share&branch=main&name=filestore"><img alt="Deploy to Koyeb" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/koyeb.svg"></a>
</details>


![Configs](https://telegra.ph/file/033408792afc4d4f1f8f6.png) 🤖

- `API_ID` - Get this from [TelegramORG](https://telegram.org)
- `API_HASH` - Get this from [TelegramORG](https://telegram.org)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `BOT_USERNAME` - You Bot Username. *(Without [@])*
- `DB_CHANNEL` - A Telegram Channel ID.
	- Make a Channel for Storing Files. We will use that as Database. Channel must be Private! Else you will be Copyright.
- `BOT_OWNER` - Bot Owner UserID
	- Put your Telegram UserID for doing Broadcast.
- `DATABASE_URL` - MongoDB Database URI
	- This for Saving UserIDs. When you will Broadcast, bot will forward the Broadcast to DB Users.
- `UPDATES_CHANNEL` - Force Sub Channel ID *(Optional)*
	- ID of a Channel which you want to do Force Sub to use the bot. 
- `LOG_CHANNEL` - Logs Channel ID
	- This for some getting user info. If any new User added to DB, Bot will send Log to that Logs Channel. You can use same DB Channel ID.


## Commands:
```
start - start the bot
clear_batch - Clear User Batch Files
status - Show number of users in DB [Owner Only]
broadcast - Broadcast replied message to DB Users [Owner Only]
ban_user - [user_id] [ban_duration] [ban_reason] Ban Any User [Owner Only]
unban_user - [user_id] Unban Any User [Owner Only]
banned_users - Get All Banned Users [Owner Only]
```

