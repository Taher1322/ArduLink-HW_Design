ArduLink Shield is a platform that brings many Arduino projects to life quickly without having to do a lot of breadboard connections.

</br>

ArduLink enables a modular plug and play approach for enthusiast to design and develop applications as suits their end goal. It is a tool that provides the ability to develop applications faster without worrying about hardware components.

</br>

This repository includes all the design files - schematics and layout

</br>

![General Block Diagram](https://github.com/Taher1322/ArduLink-Firmware/blob/main/Block_Diag-Block_Diagram_Shield.jpg)

</br>

![Schematics](https://github.com/Taher1322/ArduLink-HW_Design/blob/main/Schematics.png)

![ArduLink Shield](https://github.com/Taher1322/ArduLink-Firmware/blob/main/Screenshot%202025-03-13%20195432.png)

# Pin Mapping

| Arduino Uno/Mega  | ArduLink Shield |
| ------------- | ------------- |
| Analog Pin A0 | Moisture Sensor  |
| Analog Pin A1  | Gas Sensor MQ7  |
| Analog Pin A2 |  Ambient Light TEMT600 Sensor|
| Analog Pin A3 |  Future Expansion |
| Analog Pin A4 | I2C SDA - DAC, RTC & OLED Display |
| Analog Pin A5 | I2C SCL - DAC, RTC & OLED Display |
| Digital Pin 0 - Arduino RX | Bluetooth HC-05 TX |
| Digital Pin 1 - Arduino TX | Bluetooth HC-05 RX |
| Digital Pin 2 | Temperature and Humidity DHT11/22 Sensor |
| Digital Pin 3 | Smart NeoPixel LED's |
| Digital Pin 4 | Buzzer |
| Digital Pin 5 | Temperature DS18B20 Sensor |
| Digital Pin 6 | Ultrasonic Sensor Echo Pin |
| Digital Pin 7 | Ultrasonic Sensor Trigger Pin |
| Digital Pin 8 | Future Expansion |
| Digital Pin 9 | Push Button |
| Digital Pin 10 | SD Card Chip Select Pin |
| Digital Pin 11 | SD Card MOSI Pin |
| Digital Pin 12 | SD Card MISO Pin |
| Digital Pin 13 | SD Card SCK Pin |