# Arduino-Uno-R3-Temperature-Sensor
Project Techpoli.info

Arduino Uno R3 Temperature Sensor

Hellow Friends, in the last few monthly a demand has arisen to colect a DataCenter’s temperature and store the information in a text file.
Doing a brief research I couldn’t find a solution to attend the company’s needs, so I’ve decided to develop my own measurement temperature device.


Materials:

1-Arduino Uno R3
1-Breadboard 400 Holes
1-Potentiometer 10k
1-Sensor temperature and humidity dht11
1-Display 16×2

Arduino Code:

the Arduino’s code is sending information to a COM port. As I’m not using an ethernet interface it needs some interface to colect the temperature and humidity. To do so I’ve developed the java program as follow to colect the information through the COM port.

Java Code

The design is pretty simple.
This project is intended to be used for people interested on monitor the Server’s humidity and temperature.
The data could be imported whether to nagios or splunk to analyze and monitoring.

That’s all.
