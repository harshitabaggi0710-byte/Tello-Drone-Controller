# Tello-Drone-Controller
Control a DJI Tello drone with Python using keyboard inputs and object detection with OpenCV.

# Tello Drone Control System 🚁🎮📷

This project demonstrates controlling a **DJI Tello Drone** using Python.  
It includes basic drone control via keyboard inputs, video streaming, and **object detection** using **OpenCV**.  
The system leverages the `djitellopy` library to interface with the drone and integrates `pygame` for real-time key mapping.  



## 🔧 Libraries Used
- **djitellopy** → Python library to interface with Tello drones  
- **opencv-python** → Computer vision (video streaming, object detection)  
- **numpy** → Numerical computations  
- **pygame** → Handling keyboard inputs & creating control interface  
- **cvzone** → Simplified OpenCV utilities for detection  



## 🛠 Features
- Initialize and connect to Tello drone  
- Capture and display live video stream  
- Keyboard-based control (takeoff, landing, directional movement)  
- Object detection using pre-trained MobileNet SSD model  



## 🚀 Implementation Details
1. **Connecting to Drone**  
   - Used `djitellopy` to establish WiFi connection with Tello.  

2. **Keyboard Control**  
   - Mapped keyboard inputs using `pygame`.  
   - Functions for takeoff, landing, moving in all directions.  

3. **Object Detection**  
   - Implemented object detection with **OpenCV DNN** module.  
   - Used **SSD MobileNet v3** pre-trained model with COCO dataset.  
   - Detections drawn in real-time on drone video feed.  



## ▶️ How to Run

### 1. Install Requirements

- pip install djitellopy opencv-python numpy pygame cvzone

### 2. Connect to Drone

- Power on the DJI Tello Drone.
- Connect your computer to the drone WiFi (TELLO-XXXX).

### 3. Run Keyboard Control

- python keyboard_control.py


## Controls:

⬆️ UP → Move Forward

⬇️ DOWN → Move Backward

⬅️ LEFT → Move Left

➡️ RIGHT → Move Right

Q → Land

E → Takeoff

4. Run Object Detection
python object_detection.py

### 📌 Learning Outcomes

Gained hands-on experience with drone programming

Integrated computer vision with robotics

Implemented object detection on real-time video streams

Explored human-drone interaction with keyboard inputs


