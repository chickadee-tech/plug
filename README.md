# plug
Small, pluggable sensors

Plug is an open standard for small, space efficient sensors. It allows for varying sensor in a space constrained area.

It uses a 20 pin edge connector. It has two copies of each pin so that the plug board is reversable.

The 10 pins are:

* 3.3v
* SDA - I2C data. Pulled up by carrier
* SCL - I2C clock. Pulled up by carrier
* INT - Interrupt active low. Pulled up by carrier
* SCK - SPI Clock
* MOSI - SPI Microcontroller Out Sensor In
* MISO - SPI Microcontroller In Sensor Out
* D0 - Digital Pin
* A0 - Analog input pin. (Can also be used digitally)
* GND

All pins are shared amongst multiple plugs except D0 and A0 which are exclusive.
