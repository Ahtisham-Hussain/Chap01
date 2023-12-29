# Blink an LED

The LED is connected to Arduino pin 11. In the void setup() function, the Arduino pin defined by the LEDpin variable is defined as an OUTPUT pin, rather than an INPUTpin that would be used for input, such as measuring a voltage. In the void loop() function, the state of Arduino pin 11 is repeatedly changed from HIGH to LOW and LOW to HIGH at one-second intervals, which corresponds to changing the output voltage on the pin from 5V to 0V, and so the LED turns on and off.

## Components

- LED
- Resistor (220 ohm)
- Arduino UNO

## Project Demo

https://github.com/Ahtisham-Hussain/Chap01/assets/154002517/661d369a-5a0f-4b71-8235-517608c63dfa
