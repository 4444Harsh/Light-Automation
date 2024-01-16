# Light-Automation
Light Automation with Mobile Control Welcome to the Light Automation repository! This project allows you to effortlessly control the lighting in your room using your mobile device. Say goodbye to traditional switches and experience the convenience of smart lighting.
\\! Below is a concise README file that you can use for your IoT-based light automation project:

---

# ESP8266-Based Light Automation

Welcome to the ESP8266-Based Light Automation project! This repository contains the code and configurations to set up a smart lighting system using ESP8266, a relay module, and jumper wires. With this system, you can control your room lights through a web server hosted on the ESP8266, accessible from your mobile device.

## Components Used:

- ESP8266
- Relay Module
- Jumper Wires

## Dependencies:

- [ESP8266WiFi library](https://arduino-esp8266.readthedocs.io/en/latest/esp8266wifi/readme.html)
- [ESP8266WebServer library](https://github.com/esp8266/Arduino/tree/master/libraries/ESP8266WebServer)

## Getting Started:

1. **Clone the Repository:**

2. **Open the Arduino IDE:**
   - Install the ESP8266 board support. Follow the instructions [here](https://github.com/esp8266/Arduino#installing-with-boards-manager).

3. **Install Libraries:**
   - Install the required libraries through the Arduino Library Manager.

4. **Configure the Code:**
   - Update the SSID and Password in the code with your WiFi credentials.

5. **Upload Code to ESP8266:**
   - Connect your ESP8266 to your computer and upload the code using the Arduino IDE.

6. **Access Web Interface:**
   - Connect to the WiFi network created by the ESP8266.
   - Open a web browser and enter the IP address (default: 192.168.1.1) to access the control interface.

## Web Interface:

- The web interface allows you to control two LEDs, simulating room lights.
- Each LED has ON and OFF buttons for manual control.
- The interface displays the current status of each LED.


Happy automating!

---

Feel free to modify the sections or add more details as needed. Include any specific instructions or considerations for users working with ESP8266 and the relay module in your project.
