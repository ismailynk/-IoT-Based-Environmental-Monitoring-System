# 🌡️ IoT-Based Environmental Monitoring System

An IoT-based environmental monitoring project developed using ESP32 and DHT11 to collect temperature and humidity data and provide real-time monitoring through ThingSpeak and Telegram.

The system continuously measures environmental conditions and sends the collected sensor data to the ThingSpeak IoT platform for live visualization and remote monitoring. Additionally, a Telegram bot allows users to request current temperature and humidity readings through simple text commands.

### ✨ Key Features

- 🌡️ **Temperature Monitoring:** Collect real-time temperature data using the DHT11 sensor.
- 💧 **Humidity Monitoring:** Measure and monitor environmental humidity levels.
- 📡 **ESP32 Integration:** Collect sensor data and transmit it through Wi-Fi.
- 📊 **ThingSpeak Integration:** Send sensor readings to ThingSpeak for live data visualization and remote monitoring.
- 📈 **API-Based Monitoring:** Access real-time environmental data through the ThingSpeak API.
- 🤖 **Telegram Bot Integration:** Retrieve sensor readings remotely through Telegram.
- 💬 **Instant Temperature Queries:** Send the `temperature` command to receive the current temperature.
- 💧 **Instant Humidity Queries:** Send the `humidity` command to receive the current humidity level.
- 🌐 **Remote Monitoring:** Access environmental information without being physically connected to the sensor.
- ⚡ **Real-Time Data Communication:** Automatically transmit sensor measurements to connected platforms.

### 🔄 How It Works

1. The DHT11 sensor measures the current temperature and humidity.
2. The ESP32 reads the sensor data and connects to the internet through Wi-Fi.
3. Collected measurements are transmitted to ThingSpeak for live visualization and data monitoring.
4. The system provides access to sensor readings through the ThingSpeak API.
5. A Telegram bot receives user commands and retrieves the requested environmental data.
6. Users can request the current temperature or humidity directly through Telegram messages.

### 🛠️ Technologies Used

- ESP32
- DHT11 Temperature & Humidity Sensor
- Arduino IDE
- ThingSpeak IoT Platform
- ThingSpeak API
- Telegram Bot API
- Wi-Fi Communication
- IoT Data Monitoring

### 🎯 Project Goal

The main objective of this project was to develop a simple and practical IoT monitoring system capable of collecting environmental data and making it accessible remotely.

By integrating ESP32, ThingSpeak, and Telegram, the project combines cloud-based data visualization with interactive messaging-based monitoring, allowing users to access environmental measurements through both a web platform and a Telegram bot.
