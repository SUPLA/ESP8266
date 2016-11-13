SUPLA firmware compiled by @Zybi for board by @Espablo V.2
https://forum.supla.org/viewtopic.php?f=24&t=340

Firmware for ESP-07 with flash 1MByte:

lightswitch_x2_noFOTA_1M_eagle.flash.bin ------------> 0x00000
lightswitch_x2_noFOTA_1M_eagle.irom0text.bin --------> 0x40000


Firmware for ESP-12 with flash 1MByte and changed GPIO5 and GPIO4:

lightswitch_x2_54_noFOTA_1M_eagle.flash.bin ------------> 0x00000
lightswitch_x2_54_noFOTA_1M_eagle.irom0text.bin --------> 0x40000


Relay1  - GPIO4
Relay2  - GPIO13
BUTTON  - GPIO5  pull up / CFG MODE
Sensor1 - GPIO14 pull up / turn on/off relay1 (mode "switch" or "button")
Sensor2 - GPIO12 pull up / turn on/off relay2 (mode "switch" or "button")
DS18B20 - GPIO2  thermometer
LED RED - GPIO15 

Initial parameters for "ESP Falsh Download Tool":

CreystalFreq 26M
SPI SPEED 40 MHz
SPI MODE QIO
BAUDRATE 11520
FLASH SIZE 8Mbit (1MByte)


/////////////////////////////////////////////////////////////////
/////////////////////////////////////////////////////////////////


Firmware for ESP-12, ESP-12E, ESP-12F with flash 4MByte and changed GPIO5 and GPIO4

lightswitch_x2_54_noFOTA_4M_eagle.flash.bin ------------> 0x00000
lightswitch_x2_54_noFOTA_4M_eagle.irom0text.bin --------> 0x40000


Relay2  - GPIO13
BUTTON  - GPIO5  pull up / CFG MODE
Sensor1 - GPIO14 pull up / turn on/off relay1 (mode "switch" or "button")
Sensor2 - GPIO12 pull up / turn on/off relay2 (mode "switch" or "button")
DS18B20 - GPIO2  thermometer
LED RED - GPIO15

Initial parameters for "ESP Falsh Download Tool":

CreystalFreq 26M
SPI SPEED 40 MHz
SPI MODE QIO
BAUDRATE 11520
FLASH SIZE 32Mbit (4MByte)



// CFG MODE -----------------------------------------------------



To bring the device into configuration
mode, press and hold button for at least 5 sec. When in configuration mode,
the device goes into Access Point mode.

In order to enter or change the settings, you need to:

- Sign in at https://cloud.supla.org (registration is free of charge)
- Connect to WiFi called „SUPLA-ESP8266” from any computer with a wireless network card and Internet browser.
- Open access page: http://192.168.4.1
- Enter user name and password to the WiFi through which the device will get Internet access.
- Enter Server address, Location ID and Location Password, which will be provided once you sign in at cloud.supla.org