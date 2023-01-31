# Mdisk To VideoDownloader Bot

*A Telegram MDisk Video Downloader Bot, You can convert any mdisk link to file or video format using this bot)*

---

#### Required

- `HASH` Your API Hash from my.telegram.org
- `ID` Your API ID from my.telegram.org
- `TOKEN` Your bot token from @BotFather

#### Optional

- `WIN` Set to 1 to use Windows version, defaults to 0 which is for Linux version
- `AUTH` List of Authenticated User's ID seperated by comma (,)
- `BAN` List of Banned User's ID seperated by comma (,)

#### Premium Features (upto 4 GB Files)

- `STRING` Premium User String Session
- `TEMP_CHAT` Username or ID of Chat (Channel or Group, Private, Public), both User account and Bot should have access to messages in that chat (basically a log chat but required not optional)

---

# Commands

- Copy and Paste the commands in the Botfather

```
start - start message
help - list of commands
mdisk - usage
thumb - reply to a image document of size less than 200KB to set it as Thumbnail ( you can also send image as a photo to set it as Thumbnail automatically )
remove - remove Thumbnail
show - show Thumbnail
change - change upload mode ( default mode is Document )
```
---

# Deploy on Render
 
 * Use Render branch while deploying on Render.

 * Add environmental variables directly in Render then create web service.

 * That's it. You have Done it.

# Deploy on VPS

 * Clone the Repo
 ```
 git clone https://github.com/WebX-Divin/Mdisk-To-VideoDownloader
 ```

 * Move to the Repo Folder
 ```
 cd Mdisk-To-VideoDownloader
 ```
 * Update the VPS
 ```
 apt install update && upgrade
 ```
 * Install the requirements, this may take a while 
 ```
 pip install -r requirements.txt
 ```

 * Create a nested environment
 ```
 apt install tmux
 ```
 * Move to the nested environment
 ```
 tmux
 ```
 * Run the bot
 ```
 python3 main.py
 ```

 # Join Telegram Channel 
 - [WebXBots](https://t.me/WebXBots). Bot Updates Channel
 - Support Group [WebX-Support](https://t.me/Web_X_Support). For Bug report.

 # Credits

 - Thanks [Bipinkrish](https://github.com/bipinkrish) for this awesome source.
 - Thanks [pyrogram](https://docs.pyrogram.org/) for library.