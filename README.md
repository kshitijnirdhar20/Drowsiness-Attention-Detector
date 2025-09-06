# 🚗 Drowsiness & Attention Detector

This project is a **real-time driver drowsiness and attention monitoring system** built with **Python, OpenCV, and Mediapipe**.  
It detects **eye closure, yawning, and head tilts** to alert drivers when they lose focus — making it especially useful for **car drivers and truck drivers at night**.  

---

## 📌 Features
- 👁 **Eye Aspect Ratio (EAR)** detection to check if eyes are closing (drowsiness).
- 👄 **Mouth Aspect Ratio (MAR)** detection to detect yawning.
- 🎯 **Head Tilt Angle** calculation to check if the driver is distracted.
- 🔊 **Alarm system** using `pygame` to warn the driver.
- 📊 On-screen **visual bars** to monitor EAR, MAR, and head tilt.

---

## 🛠 Requirements
Make sure you have the following installed:

```bash
pip install opencv-python mediapipe numpy pygame
