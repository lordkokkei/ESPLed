# ESPLed
ESPLed makes it easy to control Leds on the ESP8226 and ESP32 for use as indicator lights.

## Key Features
  * **Brightness Compensation** - 
  Led power is set using a percentage from 0 to 100. This value is mapped to a 10 bit PWM value, and adjustments are made for the antilog way in which brightness is perceived by the human eye. 

  * **Active Modes** - 
  Blinking and pulsing of Leds are handled through the library.

  * **HIGH vs LOW Leds** - 
  Specify whether the Led is turned on by a logic `HIGH` or `LOW` and the library will automatically adapt `on()` an `off()` functions to compensate


