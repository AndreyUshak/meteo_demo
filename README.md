### Демо версия метеостанции в минимальной конфигурации(v071124):
___
- ESP32 4mb
- ILI9488 SPI
- Энкодер или кнопка //необязательно

#### УСТАНОВКА
- скачать flash download tool
https://www.espressif.com/en/support/download/other-tools
- соединить по схеме ESP32_ILI9488.jpg
- прошить esp32_110724_0x0.bin (meteo_2.jpg)
- подключитья к точке доступа ESP-METEO
- зайти по адресу 109.168.11.11 и указать ssid/password роутера
- при загрузке запомнить IP ESP32 или команда в порт ip или i
- просмотр экранов энкодером, кнопкой или команда в порт: n или p //next prev
- подключиться к ESP32 по FTP (esp8266/esp8266) или HTTP://xxx.xxx.xxx.xxx (ip esp32)
- скачать config.txt,cron.txt
- в config.txt заполнить 
  #TIMEZONE;;
  #lat;;
  #lon;;
- в cron.txt указать номер экрана после загрузки -scr:xx

#### остались вопросы, смотрите видео:
https://youtu.be/tIsQJwXvSxs
####  как настроить свой экран:
1) https://youtu.be/mcWuY-g43Io
2) https://youtu.be/hKhESnBBsvY

если есть желание расширить конфигурацию,
исходники под роликом.
#### плейлист
https://www.youtube.com/playlist?list=PLHqphEbvykYsgt-Dys90m4LnT5WGzmDI0
##### библиотеки в прошивке
- GFX_Library_for_Arduino https://github.com/moononournation/Arduino_GFX
- ESPRotary https://github.com/LennartHennigs/ESPRotary
- Button2  https://github.com/LennartHennigs/Button2
___
![git](https://github.com/user-attachments/assets/be710210-78bf-474b-a4e7-0ffcc4c200fd)
