 # Micropython displays reference chart 
 
 - Please report dead links
 - Please add contributions

|Controller |Type|Typical display |conn.|Typ.res.|Driver Library |Remark |
|----|----|----|----|----|----|----|
|SSD1606 |E-Paper|active matrix epaper| |128x180|[micropython-ili9341 ](https://bitbucket.org/thesheep/micropython-ili9341)|Collection of drivers |
|SSD1675 |E-Paper| | | |[ssd1675a](https://github.com/mattytrentini/ssd1675a)| |
|HD44780 |LCD Char.| | | |[lcdi2c](https://github.com/slothyrulez/lcdi2c)| |
|HD44780 |LCD Char.| | | |[micropython-charlcd](https://github.com/rdagger/micropython-charlcd)| |
|HD44780|LCD Char.| |I2C | |[micropython-i2c-lcd](https://github.com/Bucknalla/micropython-i2c-lcd)| |
|HX1230 |LCD Grap.| | |96x68 |[micropython-hx1230](https://github.com/mcauser/micropython-hx1230)| |
|LCD160CR |LCD Grap.|Small multicolor LCD TFT Touch | | |[Official LCD160CR](https://github.com/micropython/micropython/tree/master/drivers/display)| |
|PCD8544 |LCD Grap.|Nokia 5110| |84x48 |[micropython-pcd8544](https://github.com/mcauser/micropython-pcd8544)| |
|ST565 |LCD Grap.| | | |[micropython-st7565](https://github.com/nquest/micropython-st7565)| |
|ST7920 |LCD Grap.|Larger| |128x64 |[micropython-st7920](https://github.com/ShrimpingIt/micropython-st7920)| |
|FT800|LCD TFT| | | |[ ]()| |
|FT810|LCD TFT| | | |[ ]()| |
|ILI9341|LCD TFT|Medium lcd rgb 2.7”-3.2” | | |[micropython-ili9341](https://bitbucket.org/thesheep/micropython-ili9341)|Collection of drivers |
|ILI9341 |LCD TFT|| | |[micropython-ili9341](https://github.com/jeffmer/micropython-ili9341)|jeffmer|
|ILI9341 |LCD TFT|| | |[micropython-ili9341](https://github.com/tkurbad/micropython-ili9341)|ESP32 version|
|ILI934X |LCD TFT| |SPI | |[micropython-ili934x](https://github.com/tuupola/micropython-ili934x)| |
|NT7108 |LCD TFT| | | |[ ]()| |
|SH1106|LCD TFT| | | |[micropython-ili9341](https://bitbucket.org/thesheep/micropython-ili9341)|Collection of drivers |
|SSD1606|LCD TFT| | | |[micropython-ili9341](https://bitbucket.org/thesheep/micropython-ili9341)|Collection of drivers |
|SSD1963|LCD TFT| | |864x480 |[SSD1963-TFT-Library-for-PyBoard](https://github.com/robert-hh/SSD1963-TFT-Library-for-PyBoard)|Pyboard version|
|RA8875 |LCD TFT| | | |[micropython_ra8875]()| |
|ST7735|LCD TFT| | | |[micropython-ili9341](https://bitbucket.org/thesheep/micropython-ili9341)|Collection of drivers |
|ST7735 |LCD TFT| | | |[MicroPython-ST7735](https://github.com/boochow/MicroPython-ST7735)|ESP32 version|
|ST7735 |LCD TFT| | |128x128 |[MicroPython_ST7735](https://github.com/AnthonyKNorman/MicroPython_ST7735)| |
|ST7735 |LCD TFT| | | |[ST7735 ](https://github.com/hosaka/micropython-st7735)|hosaka|
|ST7735R |LCD TFT|Small color display | | |[ ]()|Adafruit |
|ST7789 |LCD TFT| | | |[st7789_mpy](https://github.com/devbis/st7789_mpy)|Fast pure-C driver|
|ST7789 |LCD TFT| | |240x240 |[st7789py_mpy](https://github.com/devbis/st7789py_mpy)|low MicroPython driver|
|ST7789 |LCD TFT|IPS TFT | | |[ ]()| |
|ST7796S |LCD TFT| | | |[ ]()| |
|HT1632C |LED Matrix|32x16 bicolor led matrix| |32x16|[micropython-ht1632c](https://github.com/vrialland/micropython-ht1632c)| |
|MAX7219 |LED Matrix|LED matrix| |8x8|[micropython-max7219](https://github.com/mcauser/micropython-max7219)| |
|TM1640 |LED Matrix|Wemos D1 Mini Matrix LED shield| | |[micropython-wemos-led-matrix-shield](https://github.com/mactijn/micropython-wemos-led-matrix-shield)||
|TM1640 |LED Matrix|Wemos D1 Mini Matrix LED shield| | |[micropython-wemos-led-matrix](https://github.com/mattytrentini/micropython-wemos-led-matrix)||
|LKM1638|LED Segm.| | | |[LKM1638](https://github.com/arikb/LKM1638)| |
|MAX7219 |LED Segm.|8-digit 7-segment LED| | |[max7219_8digit - Driver](https://github.com/pdwerryhouse/max7219_8digit)| |
|MAX7219 |LED Segm.|8-digit 7-segment LED| | |[micropython-max7219](https://github.com/JulienBacquart/micropython-max7219)| |
|MY9221 |LED Segm.|10-segment LED bar graph| | |[micropython-my9221](https://github.com/mcauser/micropython-my9221)| |
|TM1637 |LED Segm.|quad 7-segment LED| | |[micropython-tm1637](https://github.com/mcauser/micropython-tm1637)| |
|TM1638 |LED Segm.|quad 7-segment LED| | |[micropython-tm1638](https://github.com/mcauser/micropython-tm1638)| |
|TM1740 |LED Segm.|8x8 LED matrix| | |[micropython-tm1640](https://gitlab.com/robhamerling/micropython-tm1640)| |
|PCD8544|OLED| | | |[micropython-oled](https://bitbucket.org/thesheep/micropython-oled)|Collection of drivers |
|SH1106|OLED| | | |[micropython-oled](https://bitbucket.org/thesheep/micropython-oled)|Collection of drivers |
|SH1106 |OLED| | | |[]()|Waveshare oled RPI hat |
|SH1107 |OLED| | | |[ ]()|Adafruit |
|SSD1305   |OLED|Adafruit 2.23" bonnet (RPI)| | |[ ]()||
|SSD1306|OLED| | | |[micropython-oled](https://bitbucket.org/thesheep/micropython-oled)|Collection of drivers |
|SSD1306 |OLED|128x64| |128x64|[MicroPython_SSD1306](https://github.com/AnthonyKNorman/MicroPython_SSD1306)|ESP8266|
|SSD1306 |OLED|0.96" OLED | |128x64|[Official SSD1306](https://github.com/micropython/micropython/tree/master/drivers/display)| |
|SSD1309 |OLED|2.42" OLED | |128x64|[ ]()|SSD1306 w/ mods can be used|
|SSD1322 |OLED|3" to 5.5" Wide OLED display | |256x64|[ ]()| |
|SSD1325 |OLED| 2.7"| |128x64|[ ]()| |
|SSD1327 |OLED|128x128 4-bit greyscale OLED | |128x128|[micropython-ssd1327](https://github.com/mcauser/micropython-ssd1327)| |
|SSD1327 |OLED|1.5" square OLED| |128x128|[ ]()|Adafruit |
|SSD1351 |OLED| | | |[micropython-ssd1351](https://github.com/rdagger/micropython-ssd1351)| |
|UC1701X|OLED| | | |[micropython-oled](https://bitbucket.org/thesheep/micropython-oled)|Collection of drivers |

https://awesome-micropython.com/
