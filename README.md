# NodeMCU_thingspeak
A simple lua script for an ESP8266 running NodeMCU firmware that takes the input from a DHT22 temperature and humidity sensor and sends it to thingspeak.com.

# Why?
There are a few scripts out there already using the net.conn method. This kept failing for whatever reason on my setup and tracing the issue was increasingly difficult. This script uses http.post instead
