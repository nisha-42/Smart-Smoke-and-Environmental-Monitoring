# Smart Smoke and Environmental Monitoring 🚨🌱

An IoT-based system to detect smoke, gas levels (LPG, CO), and monitor environmental conditions like temperature and humidity using ESP32 and DHT/Gas sensors. Data is logged and alerts are sent in real-time.

## 🔧 Features
- Smoke and gas detection (MQ2, MQ135, etc.)
- Temperature & humidity monitoring (DHT11/DHT22)
- Real-time alerts (via buzzer, Firebase Cloud Messaging, etc.)
- Data logging to Firebase or local server
- Optional mobile app dashboard using Flutter

## 📦 Hardware Used
- ESP32 / ESP8266
- MQ2 / MQ135 Gas Sensor
- DHT11/DHT22
- Buzzer / LEDs
- Optional: Raspberry Pi (data gateway or logger)

## 📱 Mobile App
A Flutter-based app to show real-time environmental data and receive alerts.

## ☁️ Cloud Integration
- Firebase Realtime Database or Firestore
- Firebase Cloud Messaging (FCM) for push alerts

## 📁 Folder Structure
See `/hardware`, `/code`, `/mobile_app`, `/cloud`.

## 🛠️ How to Setup
1. Clone this repo
2. Upload the Arduino code to ESP32
3. Set up Firebase and mobile app
4. Power the circuit and monitor data

## 📝 License
MIT License

