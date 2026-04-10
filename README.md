# Smart Garbage Monitoring System using IoT

## 📌 Project Overview
The Smart Garbage Monitoring System is an IoT-based solution designed to monitor garbage levels in a dustbin in real-time. The system uses sensors to detect waste levels and sends alerts when the bin is full. This helps optimize waste collection, reduce overflow, and maintain cleanliness.

The project is implemented using Arduino-compatible hardware and sensors, with the main logic written in `Smart_Bin.ino`.

---

## 🎯 Features
- Real-time garbage level monitoring  
- Automatic full-bin detection  
- IoT-based data transmission  
- Low-cost and efficient design  
- Continuous monitoring system  
- Scalable for multiple bins  

---

## 🛠️ Hardware Components
- Arduino / NodeMCU / ESP8266  
- Ultrasonic Sensor (HC-SR04)  
- IR Sensor  
- Smart Dustbin  
- Jumper Wires  
- Breadboard (optional)  
- Power Supply  

---

## ⚙️ Working Principle
1. Ultrasonic sensor measures the distance between garbage and bin lid.  
2. IR sensor detects presence of waste near the opening.  
3. Microcontroller processes sensor values.  
4. If garbage level crosses threshold, bin is marked as FULL.  
5. Data is displayed on serial monitor / IoT dashboard.  
6. Alert is generated for garbage collection.  

---

### 📂 Project Structure
```
Smart-Garbage-Monitoring-System/
│
├── Smart_Bin.ino          # Main Arduino code
├── README.md              # Project documentation
├── images/                # Block diagram, circuit images (optional)
│   ├── block_diagram.png
│   └── circuit_diagram.png
│
├── docs/                  # Additional documentation (optional)
│   └── report.pdf
│
└── libraries/             # External libraries if used (optional)
```
---

## 🔌 Pin Connections (Example)

### Ultrasonic Sensor
- VCC → 5V  
- GND → GND  
- TRIG → D5  
- ECHO → D6  

### IR Sensor
- VCC → 5V  
- GND → GND  
- OUT → D7  

*(Pin numbers can be modified according to your setup)*

---

## ▶️ How to Run
1. Connect all hardware components properly.  
2. Open Arduino IDE.  
3. Load `Smart_Bin.ino`.  
4. Select board and COM port.  
5. Upload the code.  
6. Open Serial Monitor to view output.  

---

## 📊 Output
- Shows garbage level  
- Displays bin status (Empty / Half / Full)  
- Sends alert when bin is full  

---

## 🔮 Future Scope
- Add GSM module for SMS alerts  
- Add mobile application  
- Cloud data storage  
- GPS tracking for smart collection  
- Multiple bin monitoring dashboard  

---

## 👩‍💻 Author
Shivyanshi Agnihotri  
B.Tech CSE (IoT)  
Smart Garbage Monitoring System Project
