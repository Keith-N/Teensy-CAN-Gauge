# Teensy CAN Gauge

Required Hardware:
* Teensy (I used 3.2)
* 128x64 SSD1306 display (I used SPI)
* CAN transciever
* Normally open push button connected to input pin and ground (Optional)

 
SETUP NOTES
* Setup the CAN base ID and can rate to match the CAN broadcast in Tuner Studio. Found in CAN settings.
* If using a Teensy 4.0 adjust commented lines in CAN settings. Teensy 3.x and 4.x use different pinouts
* If using a different display adjust the display type for u8g2 to match, 

Pressing the input button during startup will put the gauge into demo mode. This will allow you to cycle through the different gauge types while a demo value increments.
