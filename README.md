# DrowsineesDetection_in_Vehicals
# Drowsiness Detection System (Without Using Sounds)

## 📌 Project Overview
This **Drowsiness Detection System** monitors a driver's facial expressions and eye movements using computer vision techniques. It detects signs of fatigue, such as prolonged eye closure and head tilting, and provides non-audio alerts like visual warnings or haptic feedback to prevent accidents.

## 🚀 Features
- **Real-Time Face and Eye Tracking**: Detects drowsiness based on eye closure and head position.
- **Non-Audio Alerts**: Uses visual cues (flashing screen, HUD display) or haptic feedback (seat vibrations) instead of sounds.
- **Computer Vision-Based**: Utilizes OpenCV and Dlib/Mediapipe for facial landmark detection.
- **Lightweight and Efficient**: Can run on low-power devices like Raspberry Pi or Jetson Nano.

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**: OpenCV, Dlib/Mediapipe, NumPy
- **Machine Learning**: TensorFlow/Keras (for deep learning-based detection, if needed)
- **Hardware Support**: Webcam/Dashboard camera for real-time monitoring

## 📂 Installation & Setup
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/drowsiness-detection.git
   cd drowsiness-detection
   ```
2. **Install Dependencies**
   ```sh
   pip install opencv-python dlib numpy mediapipe tensorflow
   ```
3. **Run the Project**
   ```sh
   python drowsiness_detection.py
   ```

## 🎯 How It Works
1. Captures live video feed from the camera.
2. Detects the face and tracks eye movements using facial landmarks.
3. Calculates the **Eye Aspect Ratio (EAR)** to determine drowsiness.
4. If drowsiness is detected, triggers a **non-audio alert** (flashing screen, haptic feedback, etc.).

## 📸 Demo
(Add images or GIFs showcasing the working of the system.)

## 🤝 Contribution
Feel free to fork the repo, create a feature branch, and submit a pull request!

## 📜 License
This project is open-source under the **MIT License**.

## 📧 Contact
For queries, reach out to [ayesharasheed1326@gmail.com] 
