# Tidegrow Curator

Tidegrow Curator is an experimental WiFi controller for small hydroponic systems.

Curator is responsible for automatically turning on and off the pump and light, and monitoring sensors.

## Firmware

Curator uses the [Tasmota](https://github.com/arendst/Tasmota/) firmware. See the [example rules](curator.rules).

## Pinouts

Curator has two non-standard USB host sockets:

| Signal | Description |
| ------ | ----------- |
| VBUS | Power (5V, 500mA max) |
| D+ | GPIO / Analog input (3.3V) |
| D- | GPIO / Analog input (3.3V) |
| GND | Ground |

