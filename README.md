# Chronos_ADC
Analog to Digital Conversion Firmware

This is going to control the ADC on the nrf54/52. 

12 bit ADC for 12 bit word length
fs 1000 (Make this a variable)
Create a ADC driver with these parameters.
Read in from 6 AIN pins (start with 1)
A start variable (bool, true/false)
(Little challenge, minimize power consumption)
For validation, transmit recorded values over UART, look for UART plotting tools
nRF connect

Readout with nothing connected right = fuzzy caterpillar, wrong - completely flat value
Can be either Zephyr or nrfx, whichever works
