![alt text](https://img.shields.io/badge/Python-3.9-blue)
![alt text](https://img.shields.io/badge/pyTelegramBotAPI-0.3.0-blue)
# Weather Bot for Telegram 🌦
This [Weather bot](https://t.me/WeatherShelk_bot) allows you to find out what the weather in the city today, tomorrow and the day after tomorrow.  
  
  
![Alt Text](https://puu.sh/Ihx1M/a863026904.gif)
## How to run 

  Add to environment variables (create an .env file) Telegram API key (get it from [@BotFather](https://telegram.me/botfather) when creating a new bot with /newbot command).  
`  
token='BotFather_token'
`  

To connect to the database, add and fill the fields database, user, password, host, port in the .env file.  
If you do not want to connect to the database, comment out the connect, db_users and actions functions and their calls.


Python 3,7 or higher is required to run. 

   Install libraries:  

`  
pip install -r requirements.txt  
`  

   Launch the bot:

`  
python3 WeatherBotTelegram.py  
`  
