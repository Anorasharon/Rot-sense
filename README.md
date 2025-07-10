# 🍎 RotSense - Real-Time Rotten Fruit & Vegetable Detection

> 🚀 **Before It Rots, We Spot. With AI on the Dot.**  
> A plug-and-play AI system that sees, senses, and signals spoilage — built on a Raspberry Pi using real-time object detection.

---

## 🧠 Overview

**RotSense** is a real-time, offline AI-based system that detects **rotten fruits and vegetables** using a Raspberry Pi and camera module.  
It uses a custom-trained **YOLOv5** model to classify produce as **fresh** or **rotten** and activates a physical alert using an LED or buzzer — bringing edge AI to local vendors and small retail stores.

---

## 💡 Problem Statement

In many small-scale shops and storerooms, spoiled fruits often go **unnoticed** until they affect other produce or customer health.  
While large businesses can afford cloud-based AI quality systems, smaller vendors need something affordable, portable, and **offline**.

---

## ✅ Solution

**RotSense** offers a smart and simple AI solution:
- 🧠 Detects rot using a **YOLOv5 object detection model**
- ⚡ Runs completely **offline** on a Raspberry Pi
- 🔔 Alerts instantly using **LED or buzzer**
- 💰 Low-cost, small-scale friendly
- 🔌 Easy to set up and use

---

## 🛠️ Hardware Requirements

| Component              | Role                                      |
|------------------------|-------------------------------------------|
| Raspberry Pi 4 (4GB+)  | Edge AI device to run the model           |
| Pi Camera / USB Cam    | Captures real-time images                 |
| Breadboard + Wires     | Connects alert system                     |
| LED + Resistor / Buzzer| Visual/auditory spoilage alert            |
| MicroSD Card           | With Raspberry Pi OS and files            |
| Power Adapter          | Powers the Raspberry Pi                   |

> 💡 Can also be tested on a regular laptop with a USB webcam.

---

## ⚙️ How It Works

1. 📷 Camera captures live video of produce
2. 🧠 YOLOv5 model detects **rotten** vs **fresh**
3. 🔴 If rot is detected, the system triggers an LED or buzzer
4. ✅ All detection runs **offline** using PyTorch

---

## 🧰 Software Stack

RotSense uses a powerful edge AI stack:

| Tech           | Purpose                                          |
|----------------|--------------------------------------------------|
| Python 3.8+    | Core programming language                        |
| PyTorch        | Deep learning backend to load YOLOv5             |
| OpenCV         | Video capture and frame processing               |
| YOLOv5         | Custom-trained model for object detection        |
| RPi.GPIO       | Controls Raspberry Pi pins for alert output      |
| NumPy, Pandas  | Data handling and buffer logic                   |
| torchvision    | (Optional) image transformations and debug tools |

---

## 🏆 Use Cases

- 🛍️ Grocery and Kirana shops  
- 🧊 Cold storage and warehouses  
- 🧺 Farm produce sorting units  
- 🧼 Food hygiene inspection  

---

## 🧾 Conclusion

**RotSense** is a simple yet powerful AI tool that brings computer vision to the edge — making real-time rot detection easy, affordable, and scalable.  
Designed for the real world, it can help reduce food waste and improve safety in local markets and small retail shops.

This project was created with care and purpose by **Anora Sharon Tessie S**.  
Feel free to use, learn from, or contribute to it!

---

## 🙋‍♀️ Let’s Connect

Have questions or ideas?

📧 Email: **anorasharontessie@gmail.com**  
🤝 Contributions, suggestions, and pull requests are always welcome!
