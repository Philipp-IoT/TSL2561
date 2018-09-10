# MicroPython Driver for the TSL2561 Luminosity Sensor

This module provides a driver for the TSL2561 luminosity sensor using an I2C interface. It includes the conversion of the raw sensor data to a value given in Lux. The proposed method included in the devices datasheet was used for the measurement conversion. Also a simple AGC is included to switch the gain of the sensor between 1x and 16x. The AGC was inspired by the Adafruit TSL2561 library for Arduino. 

The module was designed for the pycom WiPy 3 module. It should also work on other MicroPython ports with some adaption (of the I2C part).

## Readme

The documentation was done using Sphinx. All documentation source files are located in the docs folder.
I've hosted the compiled documentation of Read The Docs. 

[TSL2561 on ReadTheDocs.IO](https://tsl2561.readthedocs.io)

