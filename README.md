# Soil_Sensors

Soil Sensing and Monitoring using LoRa. The transmitter include sensors connected to an MSP 430. MSP periodically wakes up, measures data from sensors, and wakes up the wireless module (LoRa) to transmit the data. Sensor connections and LoRa settings are all int he transmitter code in the folder "Soil Sensors, LoRa transmitter". The LoRa gateway is implemented using Arduino based LoRa module connected to a cellular backhaul on particle argon baord. Gateway code is implemented in "LoRa gateway" folder. 
