# DMD-PCF8574
I2C connection for P10 Led Module

This library was born when trying to connect a ESP-01 module with a Freetronics P10 
board module (https://www.freetronics.com.au/products/dot-matrix-display-32x16-red). 
Using Arduino, it's possible. But the ESP-01 only has two GPIOs.  Long story short, 
the PCF8574 came to the rescue.

This is a direct port of the DMD library, but modified for the ESP-01 *ONLY*.
