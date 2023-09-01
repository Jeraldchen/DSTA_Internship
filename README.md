# DSTA_Internship
Node-RED and LoRaWAN Projects done during my internship with DSTA.

I came up with end-to-end Internet of Things (IoT) solutions for projects done during my 6 months internship with the Defence Science and Technology Agency (DSTA) using sensors that makes use of the Long Range Wide Wide Area Network (LoRaWAN) protocol. 
Here are some of the JSON code done by me using Node-RED for my projects. 

The ATAK.json file is a project done by researching on the application called Android Tactical Assault Kit (Civilian version) developed by the US Department of Defense and how I can make use of Message Queuing Telemetry Transport (MQTT) protocol to send latitude and longitude data from an Abeeway Microtracker sensor into the ATAK application itself in real time. 

The PeopleCounting.json file is a people counting project done by using the SensMax Tac-B sensor using mmWave technology and the Parametric PCR2 sensor using dual radar and the LoRaWAN protocol.
I had to create an end-to-end IoT solution by hosting my own MQTT broker using Mosquitto Broker on my localhost to store the data packets and then using Node-RED to filter and parse the data into
a time series database called InfluxDB before displaying my proposed use cases on Grafana dashboard. I got to explore basic sensor fusion concepts like using average to account for both sensors'
inaccuracies and also learn a new query language called flux which is unique to InfluxDB itself.
