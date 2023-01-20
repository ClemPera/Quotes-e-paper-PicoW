What is this project ? This project use an e-paper screen with a Pico W to show Quotes from Reddit (r/quotes) and shows time and date

![alt text](https://github.com/ClemPera/Quotes-e-paper-PicoW/blob/main/Images/Image1.jpg?raw=true)
![alt text](https://github.com/ClemPera/Quotes-e-paper-PicoW/blob/main/Images/Image2.jpg?raw=true)

Material :
- Waveshare 2.13inch e-paper hat : https://www.waveshare.com/2.13inch-e-paper-hat.htm
- Raspberry Pico W

Instructions :
- Plug the screen using the waveshare documentation : https://www.waveshare.com/wiki/Pico-ePaper-2.13
- Copy main.py and urequest.py on your Pico W
- Change the value of ssid and password in connect_wifi() function in main.py
- Change your timezone in set_time() funcion in main.py
- Enjoy :)


Inspired by this project : https://www.reddit.com/r/RASPBERRY_PI_PROJECTS/comments/o0no09/epaper_quote_scraper_and_pi_zero/
