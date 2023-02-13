# i2c / SPI character LCD backpack

<a href="http://www.adafruit.com/products/292"><img src="assets/292-10.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop
</a>

LCD backpacks reduce the number of pins needed to connect to an LCD. LCDs are a fun and easy way to have your microcontroller project talk back to you. Character LCDs are common, and easy to get, available in tons of colors and sizes. [We've written tutorials on using character LCDs with an Arduino](http://learn.adafruit.com/character-lcds) (or similar microcontroller) but find that the number of pins necessary to control the LCD can be restrictive, especially with ambitious projects. We wanted to make a 'backpack' (add-on circuit) that would reduce the number of pins without a lot of expense.

By using simple i2c and SPI input/output expanders we have reduced the number of pins (only 2 pins are needed for i2c) while still making it easy to interface with the LCD. For Arduino users, we provide a easy-to-use library that is backwards compatible with projects using the '6 pin' wiring. The breakout comes with a 2-pin and 3-pin terminal block as shown (you can snap it together to make a 5-pin terminal and then solder it to the backpack for easy wiring)

This backpack will work with any 'standard' character LCD, from 8x1 to 20x4 sizes! As long as they have a 16-pin single-line connection header at the top. [We carry a few LCDs that work great](http://www.adafruit.com/category/63_96). We suggest using our blue & white 20x4 or 16x2 LCDs. It does not work with the 16x2 OLED displays. You can try to connect our RGB 16x2 or 20x4 LCDs up but this backpack will not control the RGB backlight so you'll have to use the backpack only for the 14 digital IO pins (pins #1-14) and connect the backlight pins (#15-#18) directly to your microcontroller with 4 extra wires for color/PWM control as if they were just an RGB LED.

<b>NEW! As of February 8, 2023 - This backpack now comes with a big re-spin that makes lots of improvements:</b>

* We've added a 3-5V boost circuit so you can use this backpack to control 5V LCDs even with 3V power and logic.
* The contrast potentiometer is a lot nicer and easier to twist using a small screwdriver
* Added SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder the I2C and power lines. Just wire up to your favorite micro using a STEMMA QT adapter cable. QT Cable is not included, but we have a variety in the shop.
* Functionality and size/shape are the same - mechanically and code-wise it is a drop-in replacement.
* We've also updated this PCB with Adafruit Pinguin to make a lovely and legible silkscreen.

For advanced users, this project can be used for general purpose I/O expansion, the MCP23008 has 8 i/o pins (7 are connected) with optional pull-ups, the SPI 74HC595 has 7 connected outputs.

Note: The terminal blocks included with your product may be blue or black.

[For a detailed tutorial on usage, including an Arduino library, wiring diagrams, and files, please visit the product page](http://learn.adafruit.com/i2c-spi-lcd-backpack)

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. See license.txt for additional details.
