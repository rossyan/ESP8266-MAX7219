# ESP8266-MAX7219
Library for the ESP8266 displaying text on multiple 8x8 led matrices driven by MAX7219

This libary uses SPI interface and frame buffer to set pixels and draw text on a 4 in 1 LED Dot Matrix.



## Connecting the module(s) to the ESP8266

|LED Matrix |	ESP8266                     |
|-----------|-----------------------------|
|VCC        |	+3.3V                       |
|GND	      | GND                         |
|DIN	      |GPIO13 (HSPID)               |
|CS	        |Choose free GPIO, e.g. GPIO2 |
|CLK	      |GPIO14 (HSPICLK)             |
