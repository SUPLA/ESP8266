Sonoff z czujnikiem DHT22 podłączonym pod GPIO 14 (piąte wyprowadzenie)

Aby wejść w tryb konfiguracji wcisnąć i trzymać przycisk na module przez co najmniej 5s

Przy normalnej pracy dioda nie świeci, a przy braku połącznia z siecą wifi wolno pulsuje

Do modułu najlepiej wgrać programem Flash Download Tool z ustawieniami:

SPI SPEED 40Mhz
SPI MODE QIO
FLASH SIZE 8 Mbit (czyli 1MB)
BAUDRATE 11520

Wgrywany pod adresy:
sonoff_DHT22_noFOTA_1M_eagle.flash.bin ------------->0x00000
sonoff_DHT22_noFOTA_1M_eagle.irom0text.bin ------->0x40000
