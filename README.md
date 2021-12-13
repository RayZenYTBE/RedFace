
# 💀 RedFace (Discord Music Bot)
> RedFace is a bot made using discord.js [discordjs.guide](https://discordjs.guide)

## Preparing Everything You Need

1. Get your bot token by creating your bot first [here](https://discord.com/developers/applications)
2. Get the YouTube API key v3 [here](https://console.cloud.google.com/apis/credentials?project=trusty-ether-316813) 
3. SoundCloud doesn't provide API anymore**
4. Node.js v12.0.0 or newer. Here, we will use [replit's](https://replit.com) version. 

---

## 🔎 Making The Project

1. Import this repo to replit by copying the repo's code by clicking on the green button with "Code" text and copy the code written there. Next, go to [here](https://replit.com) and click on '+' button. Click "Import from GitHub" and paste the code. Let it load.
2. If you were asked about the Language and the Run Button, use Node.js language and `node index.js` run button.
3. Go to config.js file and edit everything there. You can add the support server link too! **REMEMBER** TOKEN, YOUTUBE API KEY, and PREFIX are required!
🚨🚨 **Commiting your token to be accessed by others or making it public is strictly prohibited.So, dont share your token in any cost or use .gitignore to hide secrets** 🚨🚨

```json
{
  "TOKEN": "", <= REQUIRED
  "YOUTUBE_API_KEY": "", <= REQUIRED
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "/", <= REQUIRED
  "PRUNING": false,
  "STAY_TIME": 30,
  "LOCALE": "en",
  "support_server": "",
  "DEFAULT_VOLUME": 100
}
```
You can also change the language by editing the LOCALE using the data below :
Currently available locales are:

• English (en)
• French (fr)
• Spanish (es)
• Turkish (tr)
• Korean (ko)
• Brazilian Portuguese (pt_br)
• Simplified Chinese (zh_cn)
• Traditional Chinese (zh_tw)

5. Next, type :
```
npm i
```

5. After the installation were done, type :
```
node index.js
```
6. Congrats! Your Music bot is now ready to use! Invite the bot by visiting the bot's discord developer portal site on OAuth2 and URL Generator!

**THANKS FOR USING REDFACE!!!**

# Links
- [Our Website](https://sites.google.com/view/atmostfeardevelopersite)
- [Host on Replit](https://replit.com/github/RayZenYTBE/RedFace)


## 📝 Features & Commands

> Note: The default prefix is '/'

* 🎶 Using YouTube URL

`/play https://www.youtube.com/c/Vevo`

* 🔎 Playing music via Name

`/play FatRat Fire`

* 🔎 Search and play

`/search Imperial March Trap Remix by Goblins from Mars`


Main Credits go to [@eritislami](https://github.com/eritislami) for making Evobot
Get evobot repo here - 
https://github.com/eritislami/evobot

Also Credits for [@drstrangegithub](https://github.com/drstrangegithub) for making ProMusic
Get ProMusic repo here -
https://github.com/drstrangegithub/ProMusic 
