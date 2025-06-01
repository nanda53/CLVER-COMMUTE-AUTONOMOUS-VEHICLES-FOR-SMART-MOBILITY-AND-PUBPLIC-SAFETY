# CLEVER COMMUTE 🚗

An **Autonomous Vehicle for Smart Mobility & Public Safety** built for efficient, safe, and intelligent transportation in urban environments.

---

## 🚀 Project Overview
**CLEVER COMMUTE** is a fully functional autonomous vehicle system that features:
- 🌐 **Smart Mobility**: Real-time route optimization and lane detection.
- 🛣️ **Obstacle Avoidance**: Intelligent detection and avoidance of obstacles.
- 🚦 **Traffic Sign & Signal Recognition**: Compliant driving decisions based on live data.
- 🛡️ **Public Safety**: Emergency stop features and pedestrian detection for enhanced safety.
- 📱 **Mobile App Integration**: Live data streaming and remote control via a custom app.

---

## 🛠️ What’s Implemented
✅ **Lane Detection** using computer vision (OpenCV & DeepLabV3).  
✅ **Obstacle and Pedestrian Detection** with deep learning (YOLOv8).  
✅ **Camera Module Integration** for live video streaming.  
✅ **Motor Control** via GPIO pins and PID controller for smooth steering.  
✅ **Real-time Data Logging** for analysis and performance optimization.  
✅ **Web Server Dashboard** for real-time data visualization (Flask/Node.js).  
✅ **Flutter-based Mobile App** for remote control and monitoring.  
✅ **Failsafe Emergency Stop** feature for public safety.

---

## 🧰 Tech Stack
- 🐍 **Python** for vehicle control and computer vision.
- 📷 **OpenCV** and **DeepLabV3** for robust lane detection.
- 🎯 **YOLOv8** for real-time obstacle and pedestrian detection.
- 🔧 **Raspberry Pi** for hardware control.
- 📡 **GPS** and **IMU** for location tracking and orientation.
- 📱 **Flutter** for mobile application development.
- 🔗 **Flask/Node.js** (optional) for real-time data visualization.

---

## 📦 Project Structure
```plaintext
📁 clever-commute-av/
 ├── docs/                # Project documentation
 ├── hardware/            # Hardware integration files
 ├── models/              # Deep learning models
 ├── scripts/             # Python scripts for sensors and control
 ├── server/              # Web server for live data
 ├── mobile_app/          # Flutter-based app
 ├── tests/               # Testing and validation
 ├── requirements.txt     # Python dependencies
 └── README.md            # Project overview