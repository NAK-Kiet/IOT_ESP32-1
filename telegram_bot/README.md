![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/esp32.jpg)

# TelegramBot with ESP32 

## Create a Telegram Bot

First going into Telegram and search for the name **botFather** as shown in the image below

![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/botfather.png)

Then in the botFather Message, chat with the **/start**, then it will reply with the following

![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/start.png)

Then create a newbot by chatting **/newbot**

![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/newbot.png)

After that choosing a name for your bot

![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/led_control.png)


## Get your Telgram ID

Go into Telegram again and search for the name **IDBot** 

![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/idbot.png)

Then you get the ID by chatting **/getid**

![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/get_id.png)


## Library Installation 

Go to arduino IDE and install some library

### Arduino JSON Library

* Go into **Sketch->Include Library-> Manage Library**


![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/include_libarary.png)

* Then search for the **arduinoJson** and install it


![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/arduinojson.png)

### Telegram Bot Library

* Download the **Telegram Bot Library** from the following link [download Telegram Board Library](https://github.com/witnessmenow/Universal-Arduino-Telegram-Bot)

* After that we need to include the download zip file to the arduino IDE by goint to **Sketch->Include Library->Add .ZIP library**


![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/add_zip_file.png)


## Programming 

* Download the code from the following link 

[Telegram Bot Code](https://github.com/Theara-Seng/IOT_ESP32/tree/main/telegram_bot)

*and copy the code in the **telegram_bot.ino**

![Esp32 Board](https://github.com/Theara-Seng/IOT_ESP32/blob/main/telegram_bot/image/code.png)

* Then in the following code you need to change this into your following wifi name and password

```sh
// Replace with your network credentials
const char* ssid = "wifi_name";
const char* password = "wifi_password";
```

* and for the telegram token and id, copy it from the telegram configuration and change it here

```sh
// Initialize Telegram BOT
#define BOTtoken "token"  // your Bot Token (Get from Botfather)

#define CHAT_ID "chatid"  // your CHAT_ID
```



