# esphome_living_room1
Trying to use esphome together with ESP32 devices and sensors, maybe also RPI4

HW Components:
living
1.ESP WROOM32 https://circuits4you.com/2018/12/31/esp32-devkit-esp32-wroom-gpio-pinout/
  a.DHT22 for humidity and temperature
  b.Capacitive Soil Humidity Sensor
  
balcon
2.ESP8266 NodeMCU https://www.theengineeringprojects.com/wp-content/uploads/2018/10/Introduction-to-NodeMCU-V3-2.png
  a.Arduino 2x Relay Module https://www.amazon.de/Ecloud-Relais-Module-Arduino-Special/dp/B00AE1P8KM
  
HA
3.Raspberry4 1GB

Installing Software:

Laptop
1.Virtual Box in Windows 7
2.Ubuntu 19.10 in Virtual Box, make sure to set enough RAM and HDD
3.esphome in Ubuntu, flashing the esp32 does not work until your user is added to dialout group
4.docker in Ubuntu, works over snap, the normall installation is broken
5.hass.io in docker: https://www.smarthomebeginner.com/install-hass-io-on-docker-linux/

raspberry4
