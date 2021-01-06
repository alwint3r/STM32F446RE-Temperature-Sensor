STM32F446RE - Internal Temperature Sensor Reading
=================================================

This repository host the firmware for reading the internal temperature sensor inside the STM32F446RE microcontroller.

Internal temperature sensor is connected to the ADC channel 18 (the same channel as VBAT).
The reading is done by reading the ADC value when the ADC conversion is complete (using interrupt).

The temperature (in Celcius unit) is then send over the UART2 every second.

This firmware is tested and working on the NUCLEO F446RE board.
