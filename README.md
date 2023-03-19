# Temperature Sensor

## Description
This is a simple Arduino code that uses the OneWire and DallasTemperature libraries to read the temperature from a DS18B20 digital temperature sensor and display it on the Serial Monitor.

## Dependencies
This code requires the following libraries to be installed in your Arduino IDE:

* OneWire
* DallasTemperature

## Hardware Requirements
This code requires the following hardware components to be connected to your Arduino board:

* DS18B20 digital temperature sensor
* 4.7k resistor (pull-up resistor)
The DS18B20 sensor should be connected to the digital pin 2 of your Arduino board, and the 4.7k resistor should be connected between the data line of the sensor and the Vcc.

## Usage
To use this code, upload it to your Arduino board and open the Serial Monitor. The temperature readings in degrees Celsius will be displayed on the Serial Monitor every second.

## Credits
This code is licensed under the MIT License. The OneWire and DallasTemperature libraries were developed by Paul Stoffregen.



