# shiftesp
This is an example project for interfacing Shift Register 8-Bit - SN74HC595 with ESP8266 version ESP-01.

# More Output for ESP-01 with Shift Register 8-Bit SN74HC595

We do love ESP8266, but it have less GPIO. Thankful, there is a way to expand ESP8266 outputs with Shift Register 8-Bit - SN74HC595. Like acknowledge, ESP-01 equipped with only two GPIO, which are GPIO0 and GPIO2. But Shift Register 8-Bit - SN74HC595 needs 3 outputs from any microcontroller to be interface with it. So, in this repository I concluded with Arduino ESP8266 source codes and Android Apps source codes.

### Arduino Source Codes ###

- WiFiWebServerShiftRegister.ino, was a combination of two source codes, which are WiFiWebServer's source code from  [Arduino ESP8266 core Github](https://github.com/esp8266/Arduino) and Shift Register 8-Bit for Arduino source code from [SparkFun Tutorial](https://learn.sparkfun.com/tutorials/sik-experiment-guide-for-arduino---v32/experiment-14-using-a-shift-register)

### Android Apps Source Codes ###

- Hybrid Apps build with Apache Cordova, in shiftesp.zip file
