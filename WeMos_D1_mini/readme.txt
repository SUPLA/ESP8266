SUPLA firmware v1.8 compiled by @Zybi

GPIO0-D3	CFG_PORT
GPIO2-D4	SHIELD DHT11/DHT22/DS18B20
GPIO4-D2	in GATEx2 B_RELAY1_PORT
GPIO5-D1	SHIELD B_RELAY1_PORT
GPIO12-D6	in GATEx2 LED_GREEN_PORT/B_SENSOR_PORT1 - operate in two modes
GPIO13-D7	in GATEx2 B_RELAY2_PORT
GPIO14-D5	in GATEx2 LED_BLUE_PORT/B_SENSOR_PORT2 - operate in two modes
GPIO15-D8	LED_RED_PORT (LED diode with a serial resistor of 270-330 ohm connect in parallel with resistor 10k on the board)
GPIO16-D0	not used

Initial parameters for "ESP Falsh Download Tool":

CreystalFreq 26M
SPI SPEED 40 MHz
SPI MODE QIO
BAUDRATE 11520
FLASH SIZE 32Mbit (4MByte)


// CFG MODE - BUTTON

To bring the device into configuration
mode, press and hold button for at least 5 sec. When in configuration mode,
the device goes into Access Point mode.

// CFG MODE - SWITCH

To bring the device into configuration
mode, in this case press cfg button min 5 times during < 5 sec. (but not too fast - press and hold button about 0,5 sec.). When in configuration mode,
the device goes into Access Point mode.

In order to enter or change the settings, you need to:

- Sign in at https://cloud.supla.org (registration is free of charge)
- Connect to WiFi called „SUPLA-ESP8266” from any computer with a wireless network card and Internet browser.
- Open access page: http://192.168.4.1
- Enter user name and password to the WiFi through which the device will get Internet access.
- Enter Server address, Location ID and Location Password, which will be provided once you sign in at cloud.supla.org

*****************************************************************
*****************************************************************
Opis opcji w nazwach plikow:

"1.8.x" - wersja oprogramowania
"restore" - z pamiecia stanu przekaznika
"NC" - sensor typu "Normaly Close"
Opis takze w plikach Readme.txt w paczkach *.rar
