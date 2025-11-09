# 🌡️ IoT-Based Temperature & Humidity Monitoring using ESP32 and DHT11  

## 📘 Project Overview  
This project monitors **real-time temperature and humidity** using the **ESP32 microcontroller** and a **DHT11 sensor**.  
The data is uploaded to the **ThingSpeak IoT Cloud**, where it is displayed using live gauges and charts.  
The entire setup is simulated on **Wokwi**, so no physical hardware is required.  

---

## 🧠 Features  
- Measures **temperature** and **humidity** continuously  
- Uploads sensor data to **ThingSpeak Cloud** using Wi-Fi  
- Displays **real-time data visualization** (gauges and graphs)  
- Simulated on **Wokwi** for testing without hardware  
- Fully open-source and easy to implement  

---

## 🧩 Components Used  
| Component | Description |
|------------|-------------|
| ESP32 | WiFi-enabled microcontroller |
| DHT11 Sensor | Measures temperature and humidity |
| Wokwi | Online ESP32 & Arduino simulator |
| ThingSpeak | IoT cloud platform for visualization |

---

## ⚙️ Circuit Connection  
| DHT11 Pin | ESP32 Pin |
|------------|-----------|
| VCC | 3.3V |
| GND | GND |
| DATA | D15 |

---

## 💻 Working Principle  
1. The ESP32 reads temperature and humidity data from the DHT11 sensor.  
2. It connects to a Wi-Fi network.  
3. Sends the data to ThingSpeak via HTTP requests using your channel API key.  
4. ThingSpeak displays the readings as live graphs and gauges.  

---

## 🧾 Arduino Code  
The Arduino `.ino` file is included in this repository.  
It contains:  
- Wi-Fi setup  
- DHT11 sensor reading logic  
- HTTP data upload to ThingSpeak  

---

## 📊 ThingSpeak Dashboard  
You can view the live IoT data here:  
🔗 [ThingSpeak Channel – Kiranmai](https://thingspeak.com/channels/3154375)

Includes:  
- 🌡️ Temperature Gauge  
- 💧 Humidity Gauge  
- 📈 Real-time chart for both readings  

---

## 🧪 Simulation Platform  
This project was tested using **Wokwi**.  
You can recreate it at 👉 [https://wokwi.com](https://wokwi.com)  

## 🏁 Output Example  
- Temperature: 24°C  
- Humidity: 40%  
- Data sent successfully to ThingSpeak  
- Live updates every 20 seconds  

---

## 📚 Applications  
- Smart Agriculture  
- Weather & Climate Monitoring  
- IoT-based Smart Homes  
- Environmental Analysis  

---

## 👩‍💻 Author  
**Kiranmai**  
B.Tech (ECE) — IoT & Embedded Systems Project  
📧 *Student Project for Academic Learning and IoT Practice*  

---

## 🏷️ Tags  
`#ESP32` `#DHT11` `#IoT` `#ThingSpeak` `#EmbeddedSystems` `#Wokwi`  
