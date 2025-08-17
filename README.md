LeafLink - IoT Plant Monitoring Dashboard 🌿
Welcome to LeafLink! This is a modern and responsive web dashboard for monitoring your plants in real-time using IoT technology. This project is designed to provide a clean and intuitive interface to connect with your automated plant watering hardware.

✨ Key Features
Real-time Monitoring: Sensor data (soil moisture, temperature, air humidity) is updated live using the MQTT protocol.

Responsive Interface: Optimized for various devices, from desktop to mobile (tested for Poco M5).

Multi-Plant Support: Easily switch between multiple plants connected to different devices (conceptual).

Data History: Interactive charts to view the history of soil moisture data over the last 24 hours.

Modern Navigation: Utilizes a sidebar on desktop and bottom navigation on mobile for a better user experience.

Simple Settings: A settings page to manage notifications and view device details.

🛠️ Tech Stack
Frontend:

HTML5

Tailwind CSS: For rapid and modern styling.

JavaScript (ES6+): For all application logic.

IoT Communication:

MQTT.js: A library to connect to an MQTT broker from the browser.

Data Visualization:

Chart.js: For creating historical sensor data charts.

Icons:

Lucide Icons: A clean and consistent icon set.

🚀 How to Run
This project is a static web application and does not require a complex build process.

Clone the Repository:

git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git

Open the File:
Simply open the index.html file in your favorite browser (like Google Chrome, Firefox, or Edge).

Connect Your Hardware:
Ensure your ESP8266/ESP32 device is programmed with the appropriate firmware and is publishing data to the same MQTT topics as defined in the index.html file.

📝 License
This project is licensed under the MIT License. See the LICENSE file for more details.
