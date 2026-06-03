# ESP32-SMART-CLASSROOM-ENVIRONMENTAL-MONITOR-AND-VENTILATION-CONTROLLER
The purpose of this project is to design and implement a smart classroom monitoring system capable of detecting temperature, humidity, air quality, light intensity, and door activity while controlling ventilation systems automatically when necessary.
1. ESP32 Pinout Configuration
Objective
To define the hardware interface between the ESP32 and the environmental control system.
System Architecture
The system consists of four main components:
1. Environmental sensors
2. ESP32 microcontroller unit
3. Wireless communication network
4. Cloud-based monitoring platformThe sensors collect environmental data from the classroom and send it to the ESP32
microcontroller for processing. The ESP32 then transmits the data to the ThingsBoard cloud
server through a Wi-Fi network. The cloud platform stores and visualizes the data using
dashboards and graphs.
