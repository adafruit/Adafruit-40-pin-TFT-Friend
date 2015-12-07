Adafruit-40-pin-TFT-Friend
==========================

These are the Eagle CAD files for the Adafruit 40-pin TFT Friend / Breakout Board

  ---->https://www.adafruit.com/product/1932

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from Adafruit!

Designed by Limor Fried/Ladyada for Adafruit Industries.
Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution

This breakout board is something we designed in-house to help us work with 'dot-clock' 40-pin TFT displays that require the RGB pixel data to be clocked in continuously. These displays have 40-pin Flex PCB (FPC) cables and often require a boost converter for the backlight LED, which makes them annoying to breadboard. To make them breadboardable, we stuck a 40-pin FPC and a FAN5333-based backlight driver with adjustable current onto a labeled breakout board. Now you can poke and probe each pin!

The backlight driver defaults to 25mA and can boost up to 24VDC for up to 7-LED strings. Check your display datasheet for the string configuration, and short out the jumpers to increase the backlight current. 