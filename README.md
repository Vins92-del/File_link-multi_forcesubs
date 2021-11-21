# File-to-link-bot

<p align="center">
  <a href="https://www.python.org">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg" width ="450">
  </a><br>
  <a href="https://t.me/CodeXBotz">
    &nbsp;<img src="https://img.shields.io/badge/Code%20%F0%9D%95%8F%20Botz-Channel-blue?style=flat-square&logo=telegram" width="130" height="18">&nbsp;
  </a>
  <a href="https://t.me/codexbotzsupport">
    &nbsp;<img src="https://img.shields.io/badge/Code%20%F0%9D%95%8F%20Botz-Group-blue?style=flat-square&logo=telegram" width="130" height="18">&nbsp;
  </a>
  <br>
  <a href="https://github.com/davi78/File_link-multi_forcesubs/stargazers">
    <img src="https://img.shields.io/github/stars/davi78/File-to-link-bot?style=social">
  </a>
  <a href="https://github.com/davi78/File_link-multi_forcesubs/fork">
    <img src="https://img.shields.io/github/forks/davi78/File-to-link-bot?label=Fork&style=social">
  </a>  
</p>


Telegram Bot untuk menyimpan Posting dan Dokumen dan dapat Diakses melalui Tautan Khusus.
Saya Kira Ini Akan Bermanfaat Bagi Banyak Orang.....😇.

##

**Jika Anda memerlukan mode lagi dalam repo atau Jika Anda menemukan bug, sebutkan di [@codexbotzsupport ](https://www.telegram.dog/codexbotzsupport)**

##
### Cara install
#### Deploy on Heroku
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/davi78/File_link-multi_forcesubs)</br>
<a href="https://youtu.be/LCrkRTMkmzE">
  <img src="https://img.shields.io/badge/How%20to-Deploy-red?logo=youtube" width="147">
</a><br>

#### Deploy in your VPS
````bash
git clone https://github.com/davi78/File-to-link-bot
cd File-to-link-bot
pip3 install -r requirements.txt
# <Create config.py appropriately>
python3 main.py
````

### Perintah khusus admin

```
/start - Perintah start

/batch - Perintah untuk membuat lebih dari satu postingan

/genlink - Perintah untuk membuat satu postingan

/users - Perintah untuk melihat statistik bot

/broadcast - Perintah broadcast ke semua users
```

### Variables 

* `API_HASH` Dapatkan API_HASH dari from my.telegram.org
* `API_ID` Dapatkan API_ID dari my.telegram.org
* `TG_BOT_TOKEN` Dapatkan Token bot dari @BotFather
* `OWNER_ID` Masukkan ID telegram OWNER
* `CHANNEL_ID` Channel ID kamu eg:- -100xxxxxxxx
* `ADMINS` ID admin
* `START_MESSAGE` Pesan start 
* `FORCE_SUB_MESSAGE` Force subs pesan 
* `FORCE_SUB_CHANNEL` Force subs 

### Extra Variables

* `CUSTOM_CAPTION` put your Custom caption text if you want Setup Custom Caption, you can use HTML and <a href='https://github.com/CodeXBotz/File-Sharing-Bot/blob/main/README.md#custom_caption'>fillings</a> for formatting (only for documents)
* `DISABLE_CHANNEL_BUTTON` Put True to Disable Channel Share Button, Default if False

### Fillings
#### START_MESSAGE | FORCE_SUB_MESSAGE

* `{first}` - User first name
* `{last}` - User last name
* `{id}` - User ID
* `{mention}` - Mention the user
* `{username}` - Username

#### CUSTOM_CAPTION

* `{filename}` - file name of the Document
* `{previouscaption}` - Original Caption

##

   **Jangan lupa bintangnya ⭐⭐⭐**

