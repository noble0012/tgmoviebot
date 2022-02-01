# Telegram Movie Bot Pyrogram updated bot

## Features

- [x] Auto Filter
- [x] Manuel Filter
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
- [x] Share TexT Feature And So Many Features


## Variables

### Required Variables
* `BOT_TOKEN`: Create a bot using [@BotFather](https://telegram.dog/BotFather), and get the Telegram API token.
* `API_ID`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `API_HASH`: Get this value from [telegram.org](https://my.telegram.org/apps)
* `CHANNELS`: Username or ID of channel or group. Separate multiple IDs by space
* `ADMINS`: Username or ID of Admin. Separate multiple Admins by space
* `DATABASE_URI`: [mongoDB](https://www.mongodb.com) URI. Get this value from [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/nj-lJfkgb6w)
* `DATABASE_NAME`: Name of the database in [mongoDB](https://www.mongodb.com). For more help watch this [video](https://youtu.be/nj-lJfkgb6w)
* `LOG_CHANNEL` : A channel to log the activities of bot. Make sure bot is an admin in the channel.
### Optional Variables
* `IMDB`: Imdb, the view of information when making True/False.
* `SINGLE_BUTTON`: choose b/w [single or double buttons](https://github.com/josprojects/tgmoviebot/issues/1) True/False.

## larger result buttons
larger results will be better for reading.

at now:
![139601786-7af37bab-549d-4f96-a65f-96e2d09b5ce0](https://user-images.githubusercontent.com/77600757/143565765-cced52c4-45f6-40e2-bfbf-2e2efd6f811f.png)

add optional larger result buttons:
![139601808-04b7726e-3e58-48a1-bb1a-d946f1d3fdcd](https://user-images.githubusercontent.com/77600757/143565860-4797e96f-5a3c-4acd-8484-6fb6a2c99bbc.png)
* `P_TTI_SHOW_OFF`: Customize Result Buttons to Callback or Url by (True = url / False = callback).
* `PICS`: Telegraph links of images to show in start message.( Multiple images can be used seperated by space )
* Check [info.py](info.py) for more

## Deploy
You can deploy this bot anywhere.

<details><summary>Deploy to Heroku</summary>
<p>
<br>
<a href="https://telegram.dog/XTZ_HerokuBot?start=MjAwOTIwMDgyMDA3L3RnbW92aWVib3QgbWFzdGVy">
  <img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>
</p>
</details>

<details>
  <summary><b>Deploy to Railway</b></summary>
<br/>

<p align="left">
<a href="https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2F200920082007%2Ftgmoviebot"
">
     <img height="30px" src="https://railway.app/button.svg">
  </a>
</p>
<a href="https://youtu.be/h6PtzFYaMxQ"><img src="https://img.shields.io/badge/How%20to%20Deploy%20on%20Railway-blue.svg?logo=Youtube"></a>
<a href="https://youtu.be/h6PtzFYaMxQ"><img src="https://img.shields.io/youtube/views/h6PtzFYaMxQ?style=social">
</a>
</p>

</details>

<details><summary>Deploy to VPS</summary>
<p>
<pre>
git clone https://github.com/josprojects/tgmoviebot
# Install Packages
pip3 install -r requirements.txt
Edit info.py with variables as given below then run bot
python3 bot.py
</pre>
</p>
</details>


## Admin commands
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
• /index - to add files from a channel
• /leave - to leave from a chat.
• /disable - do disable a chat.
* /enable - re-enable chat.
• /ban_users - to ban a user.
• /unban_users - to unban a user.
• /channel - to get list of total connected channels
• /broadcast - to broadcast a message to all Eva Maria users
```
## Support
[![telegram badge](https://img.shields.io/badge/Telegram-Group-30302f?style=flat&logo=telegram)](https://telegram.dog/jospsupportbot)
[![telegram badge](https://img.shields.io/badge/Telegram-Channel-30302f?style=flat&logo=telegram)](https://telegram.dog/JosProjects)

## Credits 
* [![Zaute-Km](https://img.shields.io/static/v1?label=Dingdi-Dev&message=devs&color=critical)](https://telegram.dog/zautebot)


## Thanks to 
 - Thanks To Dan For His Awsome [Libary](https://github.com/pyrogram/pyrogram)
 - Thanks To Mahesh For His Awesome [Media-Search-bot](https://github.com/Mahesh0253/Media-Search-bot)
 - Thanks To [Trojanz](https://github.com/trojanzhex) for Their Awesome [Unlimited Filter Bot](https://github.com/TroJanzHEX/Unlimited-Filter-Bot) And [AutoFilterBoT](https://github.com/trojanzhex/auto-filter-bot)
 - Thanks To All Everyone In This Journey

## Disclaimer
[![GNU Affero General Public License 3.0](https://www.gnu.org/graphics/agplv3-155x51.png)](https://www.gnu.org/licenses/agpl-3.0.en.html#header)    
Licensed under [GNU AGPL 3.0.](https://github.com/ZauteKm/Dingdi/blob/master/LICENSE)
Selling The Codes To Other People For Money Is *Strictly Prohibited*.
  
Deploy to railway👇

(https://railway.app/new/template?template=https%3A%2F%2Fgithub.com%2Frailwayapp%2Fexamples%2Ftree%2Fmaster%2Fexamples%2Fflask&envs=ADMINS%2CAPI_HASH%2CAPI_ID%2CAUTH_CHANNEL%2CAUTH_USERS%2CBOT_TOKEN%2CCACHE_TIME%2CCHANNELS%2CCOLLECTION_NAME%2CCUSTOM_FILE_CAPTION%2CDATABASE_NAME%2CDATABASE_URI%2CLOG_CHANNEL%2CPICS%2CSUPPORT_CHAT%2CUSE_CAPTION_FILTER&optionalEnvs=AUTH_CHANNEL%2CAUTH_USERS&ADMINSDesc=Username+or+ID+of+Admin.+Separate+multiple+Admins+by+space.&API_HASHDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&API_IDDesc=Get+this+value+from+https%3A%2F%2Fmy.telegram.org&AUTH_CHANNELDesc=ID+of+channel.Make+sure+bot+is+admin+in+this+channel.+Without+subscribing+this+channel+users+cannot+use+bot.&AUTH_USERSDesc=Username+or+ID+of+users+to+give+access+of+inline+search.+Separate+multiple+users+by+space.+Leave+it+empty+if+you+don%27t+want+to+restrict+bot+usage.&BOT_TOKENDesc=Your+bot+token&CACHE_TIMEDesc=The+maximum+amount+of+time+in+seconds+that+the+result+of+the+inline+query+may+be+cached+on+the+server&CHANNELSDesc=Username+or+ID+of+channel+or+group.+Separate+multiple+IDs+by+space&COLLECTION_NAMEDesc=Name+of+the+collections.+Defaults+to+Telegram_files.+If+you+are+using+the+same+database%2C+then+use+different+collection+name+for+each+bot&CUSTOM_FILE_CAPTIONDesc=A+custom+file+caption+for+your+files.+formatable+with+%2C+file_name%2C+file_caption%2C+file_size%2C+Read+Readme.md+for+better+understanding.&DATABASE_NAMEDesc=Name+of+the+database+in+mongoDB.+For+more+help+watch+this+video+-+https%3A%2F%2Fyoutu.be%2FdsuTn4qV2GA&DATABASE_URIDesc=mongoDB+URI.+Get+this+value+from+https%3A%2F%2Fwww.mongodb.com.+For+more+help+watch+this+video+-+https%3A%2F%2Fyoutu.be%2FdsuTn4qV2GA&LOG_CHANNELDesc=Bot+Logs%2CGive+a+channel+id+with+-100xxxxxxx&PICSDesc=Add+some+telegraph+link+of+pictures&SUPPORT_CHATDesc=Username+of+a+Support+Group+%2F+ADMIN.+%28+Should+be+username+without+%40+and+not+ID%29&USE_CAPTION_FILTERDesc=Whether+bot+should+use+captions+to+improve+search+results.+%28True+False%29&CACHE_TIMEDefault=300&COLLECTION_NAMEDefault=Telegram_files&USE_CAPTION_FILTERDefault=False&referralCode=Alif)

