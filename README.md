# precision-agriculture-system
🌾 Precision Agriculture System
This project is a smart farming solution designed to help farmers make informed decisions based on real-time data collected from their fields. Using IoT (Internet of Things) technology, the system continuously monitors environmental and soil conditions and provides crop recommendations to improve farming efficiency and yield.

🛠️ Key Features:
Sensor Integration:
The system uses various sensors to collect essential data:

Temperature Sensor – measures ambient temperature.

Humidity Sensor – checks moisture content in the air.

Soil NPK Sensor – measures the levels of Nitrogen (N), Phosphorus (P), and Potassium (K) in the soil.

Real-Time Data Monitoring:
Sensor data is collected by a microcontroller (e.g., ESP32/Arduino) and sent to a cloud platform (such as Firebase) in real time. This allows both farmers and researchers to view live updates through a web dashboard.

Crop Recommendation System:
Based on the collected data, the system intelligently recommends the most suitable crops for the current soil and environmental conditions. This helps the farmer decide what to plant for better growth and higher yield.

Web Interface:
A user-friendly web application displays the sensor data and recommended crops in a clear and organized manner.

🌐 Technologies Used:
Hardware: Sensors (Temperature, Humidity, NPK), ESP32/Arduino

Software: Embedded C / Python for sensor coding

Cloud: Firebase 

Frontend: HTML, CSS (for real-time data visualization)

🎯 Objectives:
Improve decision-making in agriculture using data-driven insights

Reduce the use of unnecessary fertilizers or wrong crop choices

Promote sustainable farming practices using affordable technology

📈 Impact:
This system aims to support small to medium-scale farmers by making precision agriculture accessible, affordable, and easy to use — helping them increase productivity while reducing environmental impact.


## 📊 Results
1. 🔌 Real-time Data Monitoring using Arduino
> 📟 Sensor data (temperature, humidity, soil NPK Values) is displayed in real-time on the Arduino IDE's Serial Monitor for debugging and monitoring.

![Result 1](Results_images/Arduino_serial_monitor_data.png)

2. 📲 Real-Time Cloud Data Logging via Firebase
> 📟 To make data accessible remotely, the real-time sensor values are pushed to Google Firebase, allowing centralized data storage and monitoring from any location. Firebase acts as the backbone for our cloud-based infrastructure, providing real-time database updates.

![Result 1](Results_images/Real_time_Firebase_data.png)


3. 🌐 The main web interface (index page) provides farmers with options to view real-time data from multiple IoT devices (e.g., Device 1, Device 2) installed across different field locations.
![Result 1](Results_images/Main_web_page.png)
  
4. 🌐 Web Interface for Real-Time Monitoring
> 📟 A custom-built web interface displays real-time sensor data from the IoT device with live values, a responsive design, and easy monitoring for farmers.

  ![Result 1](Results_images/Web_interface_Real_time_data_device_1.png)

5. 🤖 ML-Based Crop Recommendation Model
> 📟 A machine learning model trained on agricultural data (NPK, pH, rainfall, temperature, humidity) recommends the most suitable crop based on current field conditions.

![Result 1](Results_images/crop_recomandation_model.png)

6. 🌿 Crop Recommendation Web Interface
> 📟 A user-friendly web interface lets users input field parameters and instantly receive ML-based crop recommendations to simplify agronomic decision-making.

![Result 1](Results_images/web_crop_recomandation.png)


