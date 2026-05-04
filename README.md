# Advanced Drone Threat Management System

## Overview
A real-time drone detection and tracking system designed for surveillance and defence applications. The system integrates computer vision, embedded systems, and control logic to detect unauthorized drones and trigger alerts.

---

## System Architecture
- Raspberry Pi 5 → Image processing and AI inference  
- Camera Module → Captures live video  
- YOLOv8n → Real-time drone detection  
- Kalman Filter → Smooth tracking and prediction  
- GPS Module → Geofencing  
- Arduino Uno → Controls alert system (LED, buzzer, LCD)  

---

## Key Features
- Real-time drone detection  
- Kalman filter-based tracking  
- Geofence-based alert system  
- Automated alert system (LCD, LED, buzzer)  
- Evidence capture with timestamp  

---

## Results
- Detection Accuracy: 93.2%  
- Tracking Error: 1.67 m  
- Response Time: ~382 ms  
- False Alarm Rate: <3%  

---

## Testing
- 220+ drone test flights  
- Tested under:
  - Bright sunlight  
  - Cloudy conditions  
  - Presence of birds  

---

## Technologies Used
- Python  
- OpenCV  
- YOLOv8 (Ultralytics)  
- Raspberry Pi  
- Arduino  

---

## System Flow
1. Camera captures video  
2. Raspberry Pi processes frames  
3. YOLO detects drone  
4. Kalman filter refines tracking  
5. GPS checks geofence  
6. Arduino triggers alert  

---

## Status
Working prototype validated under real-world conditions
