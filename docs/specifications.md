# Specifications

## Main Features

* 9 Thermistor Inputs
    * 5 Inputs best suited for 100k NTCs, like Generic 3950 or ATC Semitec
    * 4 Inputs best suited for PT1000
* 4 Fan Outputs
    * 2 GND-switched PWM fan ports with optional tachometer support, 500mA per port
    * 2 4-pin Fan Ports, 1A maximum per port
    * Each fan output supports 5V, 12V and 24V fans
* 4 RGB Outputs (compatible with WS2812B, SK6812 and Adafruit Neopixel)
    * Integrated diagnostic SK6812 RGB LED  
    * up to 2A (shared with other 5V devices and across all 4 ports) 
* 2 I²C ports
* Integrated 12V 2A and 5V 2A step-down converters
* Usage via CAN or USB (or...use it as an USB to CAN bridge?)
* Raspberry Pi compatible mounting pattern
* Extensive Quality-of-Life Features
    * All ports are labeled on the board with the pinout and the respective pin for Klipper
    * Klipper `menuconfig` settings are printed on the board
    * Diagnostic LEDs for fan ports, DFU mode and power supply status
* Protection Features
    * Reverse Polarity Protection on the main input
    * Thermistor inputs withstand accidental short to 24V
