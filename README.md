# ESP8266 with WIFIManager and OTA

This is a blank project that incorporates WIFIManager while still allowing you to do Over The Air programming

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

You will need to install WIFIManager, ArduinoOTA, and the Adafruit ESP8266 Board Package

[Adafruit ESP8266 Board Package](https://learn.adafruit.com/adafruit-huzzah-esp8266-breakout/using-arduino-ide)
    Follow the above tutorial to install the board package to Arduino

WIFIManager 
    This library creates an Access Point. It then allows you to connect, select a wifi network and connect

ArduinoOTA
    Allows the Arduino IDE to reprogram the ESP8266 over the WIFI network

### Installing

1. Go to Sketch->Include Library-> Manage Library 
2. Search for WIFIManager
3. Install WIFIManager + ArduinoOTA

### Compiling

1. Clone this repo
2. open with Arduino
3. Click compile

### Programming

1. Connect to the ESP8266 wifi network 
2. Open your web browser try to access any website you will get redirected
3. Select your wifi network
4. Enter your wifi password

In the Arduino software
5. Tools->Port
6. Select the IP address of the ESP8266
7. Compile and upload new program

