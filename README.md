# Adafruit Metro M4 Express

Sandbox for playing with the [Adafruit Metro M4 Express](https://learn.adafruit.com/adafruit-metro-m4-express-featuring-atsamd51) board.

## Getting started

1. Update bootloader.  
2. Update CircuitPython.  
3. Update CircuitPython libraries used in `code.py`.  
4. Edit `code.py` to bring it up to date with the libraries.  

## `code.py`

In an infinite loop:
1. Swirls the NeoPixel.  
2. Reads analog voltage at A1 and writes to console.  
3. Reads digital input at D2, D3, and D4.  
   1. D2 causes a "press" of a virtual 'A'.  
   2. D3 causes the first of two audio files to be played.  
   3. D4 causes the second of two audio files to be played.  
4. Sweeps a servo.  

### Sections to update

1. Keyboard.  
2. Servo.  

## The board

1. [ATSAMD51](https://www.microchip.com/en-us/product/ATSAMD51G19A#).
2. [I/O](https://learn.adafruit.com/adafruit-metro-m4-express-featuring-atsamd51/pinouts):
   1. Power.  
   2. Digital (PWM).  
   3. Analog.  
   4. UART.  
   5. I2C.  
   6. SPI.  
   7. NeoPixel. 
   8. Parallel capture (PCC) ("camera").  
   9. SWD (debug port).  
   10. QSPI Flash (internal).
3. Programming:
   1. [CircuitPython](https://learn.adafruit.com/adafruit-metro-m4-express-featuring-atsamd51/circuitpython).  
   2. [Arduino](https://learn.adafruit.com/adafruit-metro-m4-express-featuring-atsamd51/setup).  

## Curriculum & projects

1. Get all of `code.py` to work with proper peripherals (CircuitPython).  
2. Full-stack single-board computer (hardware, HKL/SDK, firmware, software, programming).  
3. Projects with CircuitPython (Python, MicroPython).  
4. Set up for Arduino.  
5. Projects in Arduino (Arduino, C). 
