AUTHORS: 1) AARYAN
         2) ADEEP NEKLAJE
         3) ADITHYA UMESH SALIAN

# Smart Waste Management – IoT

This repository contains the complete hardware, software, and documentation for an IoT‑enabled Smart Waste Management System built using Raspberry Pi Pico/Pico W.

## 📌 Features
- Real‑time bin level detection using ultrasonic sensor
- Temperature, humidity, and gas monitoring
- OLED display for local monitoring
- LEDs and buzzer for alert indication
- Servo‑controlled lid
- Cloud data logging on ThingSpeak
- Telegram alert when bin is full or gas levels rise
- Fully documented circuit, code, and dashboard setup

## 📁 Folder overview
- **src/** → Main MicroPython source code
- **images/** → Circuit diagram, dashboard screenshots, demo assets
- **.md documentation files** → Problem statement, scope, components, schematic, code logic, dashboard setup, demo instructions

## 🛠️ Hardware Requirements
- Raspberry Pi Pico / Pico W
- HC‑SR04 ultrasonic sensor
- DHT22 temperature & humidity sensor
- MQ2 gas sensor
- SSD1306 OLED (I2C)
- Servo motor (SG90)
- Buzzer + LEDs
- Breadboard + jumper wires

## 🚀 How to Deploy
1. Flash MicroPython firmware onto Raspberry Pi Pico/Pico W
2. Open **Thonny** → connect to Pico
3. Paste and upload `smart_waste_bin.py` to the device
4. Insert your Wi‑Fi, ThingSpeak, and Telegram credentials in the config section
5. Run the script

## 🖥️ Cloud Dashboard
- Uses **ThingSpeak** for storing & visualizing:
  - Distance
  - Temperature
  - Humidity
  - Gas concentration
- Setup steps explained in `iot_dashboard.md`

## 🎥 Demo
A demo video guide is provided in `demo_video.md`. Record your circuit, OLED output, ThingSpeak dashboard, and Telegram alert.

## 📄 License

This project is released under the **MIT License**.
