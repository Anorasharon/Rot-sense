# 🍎 RotSense - Real-Time Rotten Fruit & Vegetable Detection

> 🚀 A plug-and-play AI system that sees, senses, and signals spoilage — built on a Raspberry Pi using real-time object detection.

---

## 🧠 Overview

**RotSense** is a lightweight, offline AI solution designed to detect **rotten fruits and vegetables in real time** using a Raspberry Pi and camera module. It uses a custom-trained **YOLOv5** model to classify produce as **fresh** or **rotten**, and triggers alerts using an LED or buzzer.

---

## 💡 Problem Statement

In small grocery shops and storage areas, spoiled fruits and vegetables often go unnoticed until they cause health risks or economic losses. Many vendors can't afford high-end AI systems or cloud-based quality monitoring tools.

---

## ✅ Solution

RotSense brings affordable AI to the shelf:
- Runs **offline**, in real-time.
- Uses **YOLOv5 object detection** to detect spoilage.
- Triggers a **visual (LED)** or **auditory (buzzer)** alert if rot is found.
- Built to run on a **Raspberry Pi**, making it compact and low-power.

---

## 🛠️ Hardware Requirements

- Raspberry Pi 4 (or a laptop for testing)
- Pi Camera or USB Webcam
- Breadboard + Jumper Wires
- LED and Resistor (or buzzer)
- SD Card with Raspberry Pi OS
- Power Supply and Display (for setup)

---

## 🧰 Software Requirements

- Python 3.8+
- PyTorch
- OpenCV
- YOLOv5 (custom-trained model)
- NumPy, Pandas
- `torchvision`, `matplotlib` (optional for debugging)

---

## 📦 Installation

```bash
# Clone YOLOv5 repo
git clone https://github.com/ultralytics/yolov5
cd yolov5

# Install dependencies
pip install -r requirements.txt

# Download your trained model (place it in yolov5 directory)
# For example: best.pt
