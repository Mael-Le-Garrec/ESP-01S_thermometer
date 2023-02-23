# ESP-01s Thermometer

This is my first PCB project, and it's rather simple.
The goal is to create a PCB that will have: 
  - ESP-8266 in the ESP-01S module
  - +3.3V linear regulator
  - USB-C port for power
  - DS18B20 as a temperature sensor

# Versions

## v1.0.0

This is the first version of the board. The size of the board has been decided
after measuring the temperature of the DS18B20 as a function of the distance to
the linear regulator. The further away the better, but it seemed that 7cm was
enough.

The board has:
  - ESP-01s
  - +3.3V Linear regulator with its capacitors
  - USB-C port
  - DS18B20 + a pin header to connect a second one, along with a pull-up resistor

The BOM and the PCB board can be seen at [board.html](http://htmlpreview.github.io/?https://github.com/Mael-Le-Garrec/ESP-01S_thermometer/tree/v1.0.0/html/board.html)
