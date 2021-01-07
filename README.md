# post-sensor-data-nodemcu
This project highlights on posting the sensor data retrieved from DHT temperature and humidity sensor thrugh nodemcu on a local hosted server.

Components Required : 

- NodeMCU 
- DHT 11 Sensor
- Some Jumper Wires & Cable

About the project :

This project is built with NodeMCU, an open source IOT circuit board. DHT sensor, a capacitive and humidity sensor collects the data from the sorrounding and updates it to NodeMCU board which is loaded with WiFi credentials to access to the Wifi to post data to the respected server. Here we used local host as our server to post the data retrived from the sensor.

Prerequisites :

A knowledge on NodeMCU, sensors and coding helps making project creative. 

Usage :

Connect DTH sensor to the required pins(Vin, GND, Data) on NodeMCU and powerup NodeMCU by connecting it with a PC and write the code on Arduino IDE save it with the required name. Upload the code onto the NodeMCU development board. 
Once succesfully uploaded open the local host(127.0.0.1) on any web browser and observe the readings posted by the sensor over there.
