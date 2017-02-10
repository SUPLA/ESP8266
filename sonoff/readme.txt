SUPLA FOR ITEAD SONOFF WiFi Smart Switch

sonoff_eagle.flash.bin-------->0x00000
sonoff_eagle.irom0text.bin---->0x40000

BAUDRATE: 115200
Flash Size: 1MByte
Flash speed: 40Mhz
SPI Mode: QIO

Youtube: https://www.youtube.com/watch?v=jO9yX2QVeoY

// ---------------------------------------------------
// ---------------------------------------------------
// ---------------------------------------------------

SUPLA FOR ITEAD SONOFF WiFi Smart Switch + DS18B20

sonoff_ds18b20_eagle.flash.bin--------->0x00000
sonoff_ds18b20_eagle.irom0text.bin---->0x40000

RX (GPIO3) - OneWire DAT


// CFG MODE ----------------------------------------

To bring the device into configuration
mode, press and hold button for at least 5 sec. When in configuration mode,
the device goes into Access Point mode.

In order to enter or change the settings, you need to:

- Sign in at https://cloud.supla.org (registration is free of charge)
- Connect to WiFi called „SUPLA-ESP8266” from any computer with a wireless network card and Internet browser.
- Open access page: http://192.168.4.1
- Enter user name and password to the WiFi through which the device will get Internet access.
- Enter Server address, Location ID and Location Password, which will be provided once you sign in at cloud.supla.org

***************************************************************************
***************************************************************************

Opis opcji w nazwach plikow do kompilacji opracowanych przez @Zybi

"1.8.x" - wersja oprogramowania
"restore" - z pamiecia stanu przekaznika
"inv" - z odwrocona logika swiecenia diody, czyli jej wygaszenie w przy normalnej pracy modułu
"p4" - soft dla płytki z 4 pinami, czyli czujnik na RX (GPIO3)
"p5" - soft dla płytki z 5 pinami, czyli czujnik na piątym pinie (GPIO14)
"switch_mode" i "p5" - wersja z obsluga przycisku sterowania recznego w trybie switch na piatym pinie (GPIO 14), a czujnik na RX (GPIO3)
"gate" - wersja z czasowym zalaczaniem kanalu, czyli tak jak gate_module (uwaga na wyjsciu napiecie sieci!)

Opis takze w plikach readme.txt w paczkach *.rar
