RGB-Clock
=========

RGB-Clock with STM32F1, DCF77, ESP8266, IR RC5 and LDR.

The following features are implemented (1-3) or will be implemented later (4-7)

1.) Fast STM32F103 @72MHz

2.) WS2812B RGB stripe, controlled via PWM & DMA (~0% CPU usage)

3.) DCF77 receiver for time snych

4.) ESP8266 Wifi module for HTTP interface and NTP time synch

5.) IR RC5 receiver integration

6.) LDR integrationi

7.) MicroSD Card as storage device

The board uses a standard ARM JTAG interface. In addition all remaining GPIOs and the ESP8266 are available on an external pinheader.
