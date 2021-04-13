
## Version
* Info: HC-06 Baud Rate | Date: 4/2021
* Developer: HHH

## Goal
Test functionality of HC-06 by verifying Baud Rate for later AT Commands. Notice that it happened to a lot of people including myself that I can't get to AT Mode using HC-06. It's mainly due to the wrong baud rate set up when trying to commnunicate with the HC-06.

Different than HC-05, HC-06 is in the AT mode by default when it's not connected to a Master. The only way to configure HC-06 is to directly connect to it and send AT command, no need to hold button or set High/Low to any pins. The red LED indicator keeps blinking during an initial turn on showing that it's in the AT Mode.  


## Connection
 HC06 -> Arduino Uno
1. VCC ->5V
2. GND ->GND
3. TXD ->Pin#2
4. RXD -> Voltage Divider (1k in series with 2k resistors) to Pin#3
		
## Component
1. HC-06 JY-MCU V1.06
2. Arduino Uno

## Picture for reference


![Circuit Set up](https://github.com/HHH-01/HC-06-BaudRate/blob/dcda748a6d03bd0a2f9ea9671f9224c50325e7de/Images/Circuit%20Set%20Up.jpg)

![Serial Outout](https://github.com/HHH-01/HC-06-BaudRate/blob/9209809f479bf83aee52152d6d4b9d66957d2e9d/Images/SerialOutput.PNG)
