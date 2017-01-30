# esp8266sensorpost
ESP8266 Sensor data posted to MySQL

This repository is for a network of temperature loggers I'm building to monitor temperature values at various locations around my property.

The project uses ESP8266s in the form of Sparkfun 'Things' - coded in the Arduino environment.  Data is posted to a MySQL database that is hosted on a Raspberry Pi.  The Pi also serves webpages and PHP via Apache and all network communications occur inside the DHCP of the home network.
