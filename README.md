# flaON smart home project
This is my personal smart home project. Nothing special, nothing brilliant, just a hobby of mine that runs my home.
![Image of Yaktocat](https://github.com/flax1k/flax1k.github.io/blob/master/images/flaon_project.jpg)

## Abstract
flaON is a smarthome system where I try to make the place smarter. I can view all the notifications, messages, statuses related to my home or life. Helps me keep the house alive.

## Content
## 1. List of hardware and pinouts
### 1.1. ESP8266 module
![Image of ESP8266](https://github.com/flax1k/flaON/blob/master/images/esp8266-pinout.png)
### 1.2. DHT22 sensor
![Image of DHT22](https://github.com/flax1k/flaON/blob/master/images/dht22-pinout.png)
### 1.3.Programming/flashing schema
ESP8266 VCC-------->USB-TTL VCC +3.3V

ESP8266 CH_PD------>USB-TTL VCC +3.3V

ESP8266 GND (-)---->USB-TTL GND

ESP8266 GPIO 0----->USB-TTL GND

ESP8266 RX--------->USB-TTL TX

ESP8266 TX--------->USB-TTL RX

DHT-22 Data-------->ESP8266 GPIO 2

DHT-22 VCC--------->USB-TTL VCC +3.3V

DHT-22 GND (-)----->USB-TTL GND

![Image of flashing](https://github.com/flax1k/flaON/blob/master/images/schema-flash.png)

### 1.3.Working schema
ESP8266 VCC-------->VCC+

ESP8266 CH_PD------>VCC+

ESP8266 GND (-)---->VCC-

DHT-22 Data-------->ESP8266 GPIO 2

DHT-22 VCC--------->VCC+

DHT-22 GND (-)----->VCC-

![Image of working](https://github.com/flax1k/flaON/blob/master/images/schema-working.png)

### 1.4. Programming the ESP8266

Paste the following URL to the “Additional board managers URL”: http://arduino.esp8266.com/stable/package_esp8266com_index.json

Close the screen by clicking the OK button.
Type in the search bar the 3 letters ESP. Locate and click on “esp8266 by ESP8266 Community”. Click on install and wait for a minute to download the board.

# Under construction
