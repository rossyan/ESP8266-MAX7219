# ESP8266-MAX7219
Library for the ESP8266 displaying text on multiple 8x8 led matrices driven by MAX7219

This libary uses SPI interface and frame buffer to set pixels and draw text on a 4 in 1 LED Dot Matrix.

It is tested with NodeMCU and 4in1 MAX7219 LED Dot Matrix

![dotmatrix](https://user-images.githubusercontent.com/26581663/33814574-10b79b86-ddf9-11e7-8016-6be5f08905c2.jpg)
![nodemcu](https://user-images.githubusercontent.com/26581663/33814575-10c23eb0-ddf9-11e7-8cd7-5741b049a03c.jpg)


## Connecting the module(s) to the ESP8266

|LED Matrix |	ESP8266                     |
|-----------|-----------------------------|
|VCC        |	+3.3V                       |
|GND	      | GND                         |
|DIN	      |GPIO13 (HSPID)               |
|CS	        |Choose free GPIO, e.g. GPIO2 |
|CLK	      |GPIO14 (HSPICLK)             |
