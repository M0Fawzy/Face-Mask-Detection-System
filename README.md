# 🛡️ Face Mask Detection System

A real-time face mask detection system developed using deep learning and computer vision. Built with **TensorFlow**, **Keras**, **MobileNetV2**, and **OpenCV** — deployed on both desktop (Python) and mobile (Flutter + TFLite).

## 📌 Project Overview

COVID-19 drastically changed the world, highlighting the need for public health enforcement. This project helps detect whether individuals are wearing face masks using computer vision, enabling:

- Real-time detection via webcam or images.
- Mobile deployment using Flutter + TFLite.
- High-accuracy model (98%) built with CNN and MobileNetV2.

---

## 🚀 Technologies Used

- **Python**  
- **TensorFlow & Keras**  
- **OpenCV**  
- **MobileNetV2**  
- **Flutter + Dart**  
- **TensorFlow Lite (TFLite)**

---

## 🎯 Features

- ✅ Detect if a person is wearing a mask
- ✅ Works on real-time video or image input
- ✅ Draws bounding boxes with labels and confidence score
- ✅ Detects multiple faces at once
- ✅ Android mobile app with camera/gallery detection

---

## 📊 Results

| Metric              | First Model | Final Model |
|---------------------|-------------|-------------|
| Accuracy            | 95%         | **98%**     |
| Validation Accuracy | 97%         | **98%**     |
| Loss                | 0.15        | 0.05        |
| Validation Loss     | 0.074       | 0.04        |

---

## 📱 Mobile App

Built using **Flutter**, the app loads the TFLite model for:
- 📷 Real-time camera-based detection
- 🖼️ Image-based detection from gallery
- 📊 Displays mask count, confidence, and labels

> Note: TFLite model is converted from the trained Keras model.

---
