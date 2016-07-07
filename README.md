# NodeMCU_thingspeak

## What?
A simple lua script for an ESP8266 running NodeMCU firmware that takes the input from a DHT11 temperature and humidity sensor and sends it to thingspeak.com.

## Why?
There are a few scripts out there already using the net.conn method. This kept failing for whatever reason on my setup and tracing the issue was increasingly difficult. This script uses http.post instead

## Credits
Credits go to mostly to other people for creating the calculation portion of this script...if I remember where I pulled it from I'll add it here ;)
