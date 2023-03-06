## Adafruit PiCowbell Adalogger for Pico - MicroSD, RTC & STEMMA QT PCB

<a href="http://www.adafruit.com/products/5703"><img src="assets/5703-01.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit PiCowbell Adalogger for Pico - MicroSD, RTC & STEMMA QT. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5703

### Description

Ding dong! Hear that? It's the PiCowbell ringing, letting you know that the new Adafruit PiCowbell Adalogger is in stock and ready to assist your Raspberry Pi Pico and Pico W project with handy hardware and datalogging.

The PiCowbell Adalogger is the same size and shape as a Pico and is intended to socket underneath to make your next data logging or data reading project super easy. Micro SD card socket? Yes! STEMMA QT / Qwiic connector for fast I2C? Indeed. Real Time Clock with battery backup for accurate timekeeping? Of course!

Please Note! There are a lot of possible configurations, and we stock various headers depending on how you want to solder and attach. Especially if you want the Pico on top so that the BOOTSEL button and LED are accessible.

1. Use the Pico Stacking Headers if you want to be able to plug into a breadboard or other accessory with sockets.
2. Use the Pico Socket Headers if you want to plug directly in and have a nice solid connection that doesn't have any poking-out-bits.
3. Use the Short Socket Headers for a very slim but pluggable design; note that you'll want to trim down the Pico's headers or use the short plug headers on the Pico to have a skinny sandwich.
4. Solder the PCB directly to the Pico headers - of course, this is very compact and inexpensive, but you won't be able to remove the PiCowbell.

The PiCowbell Adalogger provides you with:

* Right angle JST SH connector for I2C / Stemma QT / Qwiic connection. Provides 3V, GND, IO4 (SDA), and IO5 (SCL)
* MicroSD card holder for adding as much storage as you could possibly want for reading or writing. Connected to SPI pins 16, 18, 19 and card select on 17. Optional card detect line can be connected to pin 15.
* PCF8523 Real Time Clock with CR1220 Coin cell backup for many years of timekeeping. Set the time once using our example sketches and then you can data-log with accurate timestamps. Uses I2C.
* Reset button - Press to restart your program
* Many pads on the Adalogger has a duplicate hole pad next to it for solder-jumpering
* The ground pads have white silkscreen rectangles to easily identify, plus one long ground strip near the reset button
* Gold-plated pads for easy soldering
If using the Philhower Arduino core, the Wire peripheral is already set up to use IO4 and IO5. If using CircuitPython or MicroPython, you'll need to let the code know to look at 4+5 for SDA+SCL pins.

Does not come with a micro SD card or a coin cell battery. A CR1220 coin cell is required to use the RTC battery-backup capabilities! We don't include one by default to make shipping easier for those abroad, but we do stock them, so pick one up or use any CR1220 you have handy.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
