# ESP32-HTTPS-POST-Example
This project connects an ESP32 to a WiFi network and performs a secure HTTPS POST request to "httpbin.org". The sketch uses the WiFiClientSecure library to handle the HTTPS connection and includes the server's CA certificate for secure communication. The data sent in the POST request includes the ESP32 chip ID and a sender's name.

## Features
- Connects to a WiFi network.
- Performs a secure HTTPS POST request.
- Sends the ESP32 chip ID and a sender's name in the POST request.
- Includes the CA certificate for "httpbin.org" for secure communication.

## Requirements
- ESP32 board
- Arduino IDE
- WiFi network credentials

## Libraries Used
- WiFi.h
- WiFiClientSecure.h

## Hardware Required
- ESP32 development board
- USB cable for programming and power
- WiFi network

## Installation
1. Clone this repository.
2. Open the `.ino` file in the Arduino IDE.
3. Update the `ssid` and `password` variables with your WiFi network credentials.
4. Connect your ESP32 to the computer via USB.
5. Select the appropriate board and port in the Arduino IDE.
6. Upload the sketch to your ESP32.

## Usage
1. Ensure your ESP32 is connected to the WiFi network.
2. Open the Serial Monitor (set baud rate to 115200).
3. The ESP32 will connect to the WiFi network and perform an HTTPS POST request to "httpbin.org".
4. The response from the server will be printed in the Serial Monitor.
