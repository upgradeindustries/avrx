avrx
====

This contains basic libraries and code for the AVR-X, to be used with or without the BoardX Motherboard.

Code is provided in both plain ol' C, and Arduino C++ to:

* Print a welcome message, indicating serial connectivity
* Perform a power-on self test that scans the I2C bus for known devices, displaying what it finds
* Blink the SPI_XFER Led (on the BoardX Motherboard, otherwise you'll need to hook up an LED to the SPI clock line) 1 Hz

**Note: If you're looking for code to talk to specific add-ons, you should look for a repo for that add-on's github repo.** 
