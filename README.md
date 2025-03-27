# IoT
## This is a repository for the IoT class I took at GWU. The class was broken down into two main projects. 
## Project 1 was an environmental sensor that used Docker to create 5 containers: mosquitto, node-RED, InfluxDB, Grafana, and Portainer. This project has two principal python codes: My_Data_mqtt.py, which sends data to the internet to be pulled from other devices; and My_Data_mqtt_local.py, which only sends data locally. 

## Project 2 focuced on an design for a filamet storage and dryer. It follows the 5-layer model 
  ## Layer 1 (Perception Layer): Perseption layer: Temperature Humidity Sensor, RFID, IR sensors, Weight Sensor Pi Camera 
  ## Layer 2 (Network Layer): It primarily communicates over WiFi and MQTT
  ## Layer 3 (Middleware Layer): It uses InfluxDB as a database for the recorded data; it also allows for data streaming. It also uses Python to look for changes in humidity and prompts the user whether they want to dry the filament and the dessicant or not. 
  ## Layer 4 (Application Layer): This project primarily used a 7" touch screen display to show data locally and a GUI to display data mobially. 
  ## Layer 5 (Business Management): We will track how often the heater is needed to be used and the power consumption of the device to intidate how useful the devices is as a storage solution and how this can offset the cost of another heater or storage system. 


