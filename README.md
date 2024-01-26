## Adafruit UPDI Friend USB Serial UPDI Programmer PCB

<a href="http://www.adafruit.com/products/5879"><img src="assets/5879.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit UPDI Friend USB Serial UPDI Programmer. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5879

### Description

UPDI stands for Unified Program and Debug Interface, but this board is so smol and cute that we will call it the Unusually Playful Device Interfacer and pat its head when it does a good job. It's designed to make programming modern ATtiny chips very easy because it has 3V or 5V power and logic select, power and transmit indicator LEDs, and a quick cable for poking into a breadboard.

We have been working a lot with ATtiny816, ATtiny817 and ATtiny1616 chips lately, as for our seesaw boards. And we're often needing to program them with a CP2102-based breakout with a 1K resistor soldered between the RX and TX pins. But we were hankering for a nicer programmer!

This UPDI Friend makes programming such chips very easy:

* Select between 3V or 5V power and logic - the 3V regulator can source up to 500mA so it can run even big projects. 
* CH340E USB Serial converter chip with cross-platform drivers
* 1K Loop-back Resistor between RX and TX
* USB Type C for data and power connection to any computer
* JST SH cable included for quick plugging into a breadboard - you can get another JST SH 3-pin cable with sockets or with pin header here.
* 0.1" spaced breakout holes for custom connections.
* Green power OK LED
* Red serial activity LED
* Inspired by this [open-source hardware design](https://github.com/wagiminator/AVR-Programmer/tree/master/SerialUPDI_Programmer) from [Stefan Wagner](https://github.com/wagiminator)!

We use Arduino IDE with the megaTinyCore board support package installed, simply select "Serial UPDI" as the programmer type, we use 230Kbps but 56Kbps is also good.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
