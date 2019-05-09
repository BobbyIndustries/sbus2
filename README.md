# SBUS2-Telemetry
Arduino Library for sending Futaba SBUS2 Telemetry based on Atmega 328P (Atmega328PB in progress...)

## Hardware

Tested with Arduino Pro Mini with 8MHz and 16MHz -> with external Inverters

Tested with Futaba T14SG;T18MZ and T10J

Tested with R7008 and R3006SB


### Inverter Schematic

SBUS2       ---  --- 1K <---Inverter <--- TXD/D1
      
            |

            |

            --------------> Inverter ---> RXD/D0


## Arduino IDE

Tested with Version 1.8.5


## Version

0.1     created

0.2     Inverter instead of 3-State Buffer

0.3     16MHz support, new API


### Original Code for Atmel Studio 7
https://bitbucket.org/iBartk/multisensor/overview

Author: Bart Keser

Project: Castle Creation Telemetry to Futaba Telemetry Converter

Ported to Arduino by BrushlessPower

