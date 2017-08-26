SUPLA WIFI GATE MODULE

gate_module_eagle.flash.bin-------->0x00000
gate_module_eagle.irom0text.bin---->0x40000

-OR-

gate_module_dht11_eagle.flash.bin-------->0x00000
gate_module_dht11_eagle.irom0text.bin---->0x40000

-OR-

gate_module_dht22_eagle.flash.bin-------->0x00000
gate_module_dht22_eagle.irom0text.bin---->0x40000


PORT SETTINGS:

  [CHANNEL0] RELAY1 GPIO4
  [CHANNEL1] RELAY2 GPIO13
  CFG BUTTON GPIO5

  LED 
      - GREEN GPIO12
      - BLUE GPIO14

  [CHANNEL2] INPUT_PORT1 GPIO12
  [CHANNEL3] IMPUT_PORT2 GPIO14

  GPIO12,GPIO14 operate in two modes. In and Out (In - INPUT, Out - LED)

  [CHANNEL4] DS18B20/DHT11/DHT22 Sensor GPIO2

----------------------------------------------------------
----------------------------------------------------------
----------------------------------------------------------

gate_module_wroom-eagle.flash.bin-------->0x00000
gate_module_wroom-eagle.irom0text.bin---->0x40000

WROOM PORT SETTINGS:

  [CHANNEL0] RELAY1 GPIO4
  [CHANNEL1] RELAY2 GPIO14
  CFG BUTTON GPIO13

  LED
      - GREEN GPIO5
      - BLUE GPIO12

  [CHANNEL2] INPUT_PORT1 GPIO5
  [CHANNEL3] IMPUT_PORT2 GPIO12

  GPIO5,GPIO12 operate in two modes. In and Out (In - INPUT, Out - LED)

  [CHANNEL4] DS18B20 Sensor GPIO2

----------------------------------------------------------
----------------------------------------------------------
----------------------------------------------------------

gate_module2_wroom-eagle.flash.bin-------->0x00000
gate_module2_wroom-eagle.irom0text.bin---->0x40000

WROOM PORT SETTINGS:

  [CHANNEL0] RELAY1 GPIO4
  [CHANNEL1] RELAY2 GPIO5
  CFG BUTTON GPIO13

  LED
      - GREEN GPIO12
      - BLUE GPIO14

  [CHANNEL2] INPUT_PORT1 GPIO12
  [CHANNEL3] IMPUT_PORT2 GPIO14

  GPIO5,GPIO12 operate in two modes. In and Out (In - INPUT, Out - LED)

  [CHANNEL4] DS18B20 Sensor GPIO2

------------------------------------------------------
------------------------------------------------------
------------------------------------------------------

gate_module_esp01_eagle.flash.bin-------->0x00000
gate_module_esp01_eagle.irom0text.bin---->0x40000

PORT SETTINGS:

[CHANNEL0] RELAY GPIO0
BUTTON GPIO2

------------------------------------------------------
------------------------------------------------------
------------------------------------------------------

gate_module_esp01_ds_eagle.flash.bin-------->0x00000
gate_module_esp01_ds_eagle.irom0text.bin---->0x40000

PORT SETTINGS:

[CHANNEL0] RELAY GPIO3
[CHANNEL1] DS18B20 GPIO2
BUTTON GPIO0

Manuals:
-EN-
http://www.instructables.com/id/ESP8266-and-Relay-Control-Using-Smartphone/
-PL-
http://majsterkowo.pl/esp8266-i-sterowanie-przekaznikiem-przy-pomocy-smartfona/

