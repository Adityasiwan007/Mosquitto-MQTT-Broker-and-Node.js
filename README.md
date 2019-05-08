# Mosquitto-MQTT-Broker-and-Node.js
Connection of ESP32 to Node.js Using MQTT Broker (Mosquitto)
Mosquitto is a lightweight open source message broker that Implements MQTT versions 3.1 and 3.1.1.



It is written in C by Roger Light, and is available as a free download for Windows and Linux and is an Eclipse project.

Depending on the install it will probably be started automatically on system startup.

On Windows you can stop the service if it is running by using the control panel>admin>services.

# You can also the net command:

net stop mosquitto
# On Linux use:

sudo service mosquitto stop

# Starting from command line is the best option when testing and to do that use:

Windows and LInux

mosquitto -v   #start in verbose mode

# To see other start options use:

mosquitto -h

This file contains the sample code for mosquitto code

