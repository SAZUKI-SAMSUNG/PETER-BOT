<p align="center">
  <img src="assets/logo.jpg" alt="https://telegra.ph/file/73ad5f7b9ac871d08d058.jpg">
</p>
<h1 align="center">
  <b>PETER BOT-V1</b>
</h1>


## Features

- [x] Auto Filter
- [x] Manual Filter
- [x] IMDB
- [x] Admin Commands
- [x] Broadcast
- [x] Index
- [x] IMDB search
- [x] Inline Search
- [x] Random pics
- [x] ids and User info 
- [x] Stats, Users, Chats, Ban, Unban, Leave, Disable, Channel
- [x] Spelling Check Feature

## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com).
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this 
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )


## Deploy
You can deploy this bot anywhere.

<i>**[Watch Deploying Tutorial...](https://youtu.be/1G1XwEOnxxo)**</i>

<details><summary>Deploy To Heroku</summary>
<p>
<br>
<a href="https://heroku.com/deploy?template=https://github.com/SAZUKI-SAMSUNG/PETER-BOT">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

#Deploy on Railway


[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2FSAZUKI-SAMSUNG%2FPETER-BOT&envs=API_ID%2CAPI_HASH%2CAPI_ID%2CAUTH_CHANNEL%2CAUTH_USERS%2CBOT_TOKEN%2CCACHE_TIME%2CCOLLECTION_NAME%2CCUSTOM_FILE_CAPTION%2CDATABASE_NAME%2CDATABASE_URI%2CIMDB%2CIMDB_TEMPLATE%2CLOG_CHANNEL%2CP_TTI_SHOW_OFF%2CPICS%2CSINGLE_BUTTON%2CSUPPORT_CHAT%2CUSE_CAPTION_FILTER&optionalEnvs=AUTH_CHANNEL%2CAUTH_USERS%2CCACHE_TIME%2CCOLLECTION_NAME%2CCUSTOM_FILE_CAPTION%2CDATABASE_NAME%2CIMDB%2CIMDB_TEMPLATE%2CP_TTI_SHOW_OFF%2CPICS%2CSINGLE_BUTTON%2CSUPPORT_CHAT&API_IDDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&API_HASHDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&AUTH_CHANNELDesc=Username+or+ID+of+users+to+give+access+of+inline+search.+Separate+multiple+users+by+space.+Leave+it+empty+if+you+don%27t+want+to+restrict+bot+usage.&AUTH_USERSDesc=Username+or+ID+of+users+to+give+access+of+inline+search.+Separate+multiple+users+by+space.+Leave+it+empty+if+you+don%27t+want+to+restrict+bot+usage.&BOT_TOKENDesc=Your+bot+token.&CACHE_TIMEDesc=The+maximum+amount+of+time+in+seconds+that+the+result+of+the+inline+query+may+be+cached+on+the+server&COLLECTION_NAMEDesc=Name+of+the+collections.+Defaults+to+Telegram_files.+If+you+are+using+the+same+database%2C+then+use+different+collection+name+for+each+bot&CUSTOM_FILE_CAPTIONDesc=Add+any+text+or+caption+for+files+in+the+bot&DATABASE_NAMEDesc=Name+of+your+database+eg%3A%28pushpareju%3Bsazuki%29&DATABASE_URIDesc=MongoDB+uri.+++Or+MongoDB+link&IMDBDesc=Imdb%2C+the+view+of+information+when+making+True%2FFalse&IMDB_TEMPLATEDesc=Custom+IMDB+Template.++Add+any+caption+for+moviephoto+with+caption&LOG_CHANNELDesc=Bot+Logs%2CGive+a+channel+id+with+-100xxxxxxx&P_TTI_SHOW_OFFDesc=Customize+Result+Buttons+to+Callback+or+Url+by+%28True+%3D+url+%2F+False+%3D+callback%29&PICSDesc=Add+some+telegraph+link+of+pictures+.&SINGLE_BUTTONDesc=choose+b%2Fw+single+or+double+buttons+&SUPPORT_CHATDesc=Username+of+a+Support+Group+%2F+ADMIN.+%28+Should+be+username+without+%40+and+not+ID%29&USE_CAPTION_FILTERDesc=Whether+bot+should+use+captions+to+improve+search+results.+%28True+False%29&referralCode=Tgpushpareju)

<details><summary>Deploy To VPS</summary>
<p>
<pre>
git clone https://github.com/Aadhi000/Ajax
# Install Packages
pip3 install -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>


## Commands
```
• /logs - to get the rescent errors
• /stats - to get status of files in db.
* /filter - add manual filters
* /filters - view filters
* /connect - connect to PM.
* /disconnect - disconnect from PM
* /del - delete a filter
* /delall - delete all filters
* /deleteall - delete all index(autofilter)
* /delete - delete a specific file from index.
* /info - get user info
* /id - get tg ids.
* /imdb - fetch info from imdb.
• /users - to get list of my users and ids.
• /chats - to get list of the my chats and ids 
• /index  - to add files from a channel
• /leave  - to leave from a chat.
• /disable  -  do disable a chat.
* /enable - re-enable chat.
• /ban  - to ban a user.
• /unban  - to unban a user.
• /channel - to get list of total connected channels
• /broadcast - to broadcast a message to all Eva Maria users
```

𝙳𝙴𝚅𝙴𝙻𝙾𝙿𝙴𝚁 ›› [➪𝚂𝙰𝚉𝚄𝙺𝙸ㅤ𝚂𝙰𝙼𝚂𝚄𝙽𝙶✞︎🇮🇳[OFFLINE]](https://t.me/TEAM_KERALA)

𝙳𝙴𝚅𝙴𝙻𝙾𝙿𝙴𝚁 ›› [𝙿𝚄𝚂𝙷𝙿𝙰𝚁𝙴𝙹𝚄-𝚃𝙶[OFFLINE]](https://t.me/pushpa_Reju)                                                                                                                                       
𝙶𝚁𝙾𝚄𝙿 ›› [𝐌𝐨𝐯𝐢𝐞𝐬 𝐖𝐨𝐫𝐥𝐝](https://t.me/MoviesWorld_Group)                                             
𝙲𝙷𝙰𝙽𝙽𝙴𝙻 ›› [𝐌𝐖 𝐔𝐩𝐝𝐚𝐭𝐞𝐬](https://t.me/Minnal_Murali2021HD)
