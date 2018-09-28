# Multiboard by Espablo
Supla for ESP8266
Firmware v2.7.2

Source code: https://github.com/SUPLA/supla-espressif-esp

Description https://forum.supla.org/viewtopic.php?f=11&t=3843

<b>Supported modules:</b><br />
<b>- inCan,</b><br />
    GPIO2 - Temperature<br />
    GPIO4 - Sensor1<br />
    GPIO16 - Sensor2<br />
    GPIO14 - Button1<br />
    GPIO12 - Button2<br />
    GPIO5 - Relay1<br />
    GPIO13 - Relay2<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO4 - Input CFG (x10)<br />
    GPIO2 - LED CFG<br />

<b>- inCan RollerShutter,</b><br />
    GPIO2 - Temperature<br />
    GPIO4 - Sensor1<br />
    GPIO16 - Sensor2<br />
    GPIO14 - Button1<br />
    GPIO12 - Button2<br />
    GPIO5 - Relay1<br />
    GPIO13 - Relay2<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO4 - Input CFG (x10)<br />
    GPIO2 - LED CFG<br />

<b>- SENSORS x8,</b><br />
    GPIO2 - Temperature<br />
    GPIO4 - Sensor1<br />
    GPIO5 - Sensor2<br />
    GPIO16 - Sensor3<br />
    GPIO12 - Sensor4<br />
    GPIO13 - Sensor5<br />
    GPIO14 - Sensor6<br />
    GPIO3 - Sensor7<br />
    GPIO1 - Sensor8<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO2 - LED CFG<br />

<b>- RELAYS x9,</b><br />
    GPIO2 - Temperature<br />
    GPIO1 - Relay1<br />
    GPIO3 - Relay2<br />
    GPIO4 - Relay3<br />
    GPIO5 - Relay4<br />
    GPIO12 - Relay5<br />
    GPIO13 - Relay6<br />
    GPIO14 - Relay7<br />
    GPIO15 - Relay8 - this port must have LOW after enabling or resetting the module<br />
    GPIO16 - Relay9<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO2 - LED CFG<br />

<b>- SONOFF BASIC,</b><br />
    GPIO3 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO1 - Button2<br />
    GPIO12 - Relay1<br />
    GPIO14 - Sensor1<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />

<b>- SONOFF TH,</b><br />
    GPIO14 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO12 - Relay1<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />

<b>- SONOFF TOUCH,</b><br />
    GPIO2 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO12 - Relay1<br />
    GPIO2 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />

<b>- SONOFF TOUCH DUAL,</b><br />
    GPIO2 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO9 - Button2<br />
    GPIO12 - Relay1<br />
    GPIO5 - Relay2<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO9 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />

<b>- SONOFF TOUCH TRIPLE,</b><br />
    GPIO2 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO9 - Button2<br />
    GPIO10 - Button3<br />
    GPIO12 - Relay1<br />
    GPIO5 - Relay2<br />
    GPIO4 - Relay3<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO13 - LED CFG<br />

<b>- SONOFF_4CH,</b><br />
    GPIO2 - Temperature<br />
    GPIO0 - Button1<br />
    GPIO9 - Button2<br />
    GPIO10 - Button3<br />
    GPIO14 - Button4<br />
    GPIO12 - Relay1<br />
    GPIO5 - Relay2<br />
    GPIO4 - Relay3<br />
    GPIO15 - Relay4<br />
    GPIO0 - Button Configure (x10)<br />
    GPIO2 - LED CFG<br />

<b>- Yunshan,</b><br />
    GPIO3 - Temperature<br />
    GPIO1 - Button1<br />
    GPIO4 - Relay1<br />
    GPIO5 - Sensor1<br />
    GPIO0 - Button Configure (5s)<br />
    GPIO2 - LED CFG<br />

-------------------------------------------------

Initial parameters for "ESP Falsh Download Tool":

CreystalFreq    26M

SPI SPEED       40 MHz

FLASH MODE      DOUT

BAUDRATE        115200

-------------------------------------------------

FLASH SIZE      8Mbit (1MByte)

multiboard_1024_dout_eagle.flash.bin-------->0x00000

multiboard_1024_dout_eagle.irom0text.bin---->0x40000


