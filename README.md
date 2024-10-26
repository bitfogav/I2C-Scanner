Swordfish Basic - for 18F microcontrollers. 
https://www.sfcompiler.co.uk

12c scanner code:

I needed a way of checking the address of a device on the I2C bus, so I decided to come up with a simple prog to scan the I2C bus and to display the address on a serial monitor.
The subroutine will only display the address of the device and not the "read address", the read address is the address +1.
Also the prog will scan the bus for all the connected devices, and will show the results on the serial monitor, so it is very handy. 
