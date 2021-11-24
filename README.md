# IOT-Home-Monitoring-System

This project is a home monitoring system that is controlled using an Arduino Nano 33 IOT and the Arduino Cloud. I am currently waiting on parts to proceed with the project. So far I have an ultrasonic sensor that returns the distance of an object in its range, a dht11 temperature and humidity sensor that gives temperature in both Celcius and Ferenheit along with humidity and a LED lgiht. All of which are controlled by the cloud widgets.


Possible Upgrades:

First I will be buying a relay module and replace the led light with my room light and control that through a switch widget on the cloud.

With the ultrasonic sensor a possible upgrade is to have it log/ alert when someone is near something such as my room or computer using the HC SR04 ultrasonic sensor and a buzzer along with the messenger widget on the cloud to log if it is within a certain range and the Gauge widget to view the live ultrasonic sensor readings.

For the DHT11 sensor I have two possible options:

First:

Home thermometer 1:

I can connect the arduino to the thermostat and the cloud. I can use the cloud value widgets to view the temperature and humidity along with using the slider widget to controll the temperature and a switch widget to get from heat to cool and vice versa.

Home thermometer 2:

The second version is essentialy the same but the thermostat controlling is automated. you will be able to set certaint temperatures for certain times and also set limits if the tempereature of the house exceeds a certain point the thermostat is changed accordingly.

Second:

The second idea is to make a automated plant monitoring/maintainig system. The system will periodically monitor soil, temperature, humidity, sunilight, and heat and do task accordingly.

Widgets so far:


