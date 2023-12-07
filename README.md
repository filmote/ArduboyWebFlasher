# Arduboy Web Flasher

This is a simple online tool that uses the web serial api to flash the Arduboy.

It is specifically designed for use with the Arduboy FX, although some features may still work with the original Arduboy.

## How to use

1. Drag & Drop a .bin or .hex file anywhere within the page
2. Click reset if the Arduboy FX is not at the loader menu (bootloader)
3. Click Upload once the Arduboy FX is on the loader menu (bootloader)

## To-do

1. Clean up code - Maybe
2. Update UI
3. Use files from the web?


## Possibly To-do

1. Ability to backup .hex and .bin file from device
2. ability to backup and upload EEPROM from device

## Want to-do / Need Help

1. Making the code into a library that can easily be embedded into websites.

# Acknowledgements

Thank you to @Mr. Blinky for his help with the Arduboy FX

Based on code by Benjamin Naigener https://github.com/benjaminaigner/avr109-webserial

@noopcat for [avrgirl-arduino](https://github.com/noopkat/avrgirl-arduino) which provided the HTML code.

@bminer for [intel-hex.js](https://github.com/bminer/intel-hex.js) which provided the Intel HEX file parser




