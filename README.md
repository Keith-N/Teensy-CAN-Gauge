# Teensy CAN Gauge

Required Hardware:
*Teensy (I used 3.2)
*128x64 SSD1306 display (I used SPI)
*CAN transciever
*Normally open push button (Optional)

 
* SETUP NOTES
* Setup the CAN base ID and can rate to match the CAN broadcast in Tuner Studio. Found in CAN settings.
* If using a Teensy 4.0 adjust commented lines in CAN settings. Teensy 3.x and 4.x use different pinouts
* If using I2C for the display adjust commented lines in display settings

Teensy 4.x and I2C are untested.
