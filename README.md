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

## To update

1. Keyboard.  
2. Servo.  
