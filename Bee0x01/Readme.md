# Bee0x01 - DEFCON30

## The Bee

* 6 WS281b "NeoPixel" LEDs
* ESP-M3 (ES8285) Wireless
* Voltage handling for 3.3V to 5V up conversion and logic shifting
* UART -> ESP-M3 - 6 pin for FTDI connectors
* ESP-M3 GPIO0 breakout from unpopulated pin and jumper
* SAO (Shitty Add-on) header v1.69bis

## The Bee Code
* Bee0x01 Game
* Wireless AP to BeeConsole
* 3 blinking modes 
* 3 unlocakable blinking modes

### Connecting to the Bee - Play the Game!

To connect to Bee0x01, associate your wireless client with browser (eg. your smartphone) to Bee0x01_## (where ## is the number on the back of the bee). Open your browser to http://192.168.0.1 

Click the radio buttons to select the blinking mode, or play the choose-your-own-adventure game to unlock more modes!

### Notes & Cautions

_LED tolerances and the SAO Standard_

This bee is designed to adhere to the current limitations of the SAO v1.69bis standard. Current draws should be close or under 1.1millihorsepower (about 250mA) from the host badge. Changing the blinking patterns, brightness, colors, or duration could cause the current to overdraw to support the LEDs. Change code with caution!

## Wiring 

To be added
