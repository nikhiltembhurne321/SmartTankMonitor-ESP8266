# SmartTankMonitor-ESP8266 🚰📶

An IoT-based water level monitoring and control system using ESP8266, an ultrasonic sensor, a buzzer, and a relay. This project displays the real-time water level on a web page hosted by the ESP8266 and triggers a buzzer or motor based on predefined water levels.

## 🔧 Features
- Real-time water level monitoring via a web interface
- Buzzer alert when tank is very low or full
- Motor control using relay
- Responsive web page with live updates using JavaScript
- Clean and modern HTML/CSS design

## 📡 Hardware Used
- ESP8266 (NodeMCU)
- Ultrasonic Sensor (HC-SR04)
- Relay Module
- Buzzer
- Jumper wires and Breadboard

## ⚙️ Pin Configuration

| Component     | ESP8266 Pin |
|---------------|-------------|
| Ultrasonic Trig | D7          |
| Ultrasonic Echo | D8          |
| Buzzer         | D0          |
| Relay          | D2          |



## 🔌 How to Use
1. Connect the components as per the pin configuration.
2. Open `WaterLevelMonitor.ino` in Arduino IDE.
3. Enter your Wi-Fi credentials:
   ```cpp
   const char* ssid = "Your_WiFi_SSID";
   const char* password = "Your_WiFi_Password";
