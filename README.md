# 🏆 Real-Time Object Detection using MobileNet-SSD  

## 📌 Overview  
This project implements **real-time object detection** using the **MobileNet-SSD** model in the **Caffe deep learning framework**.  
It can detect multiple objects in images and live video streams using OpenCV’s deep learning module (`cv2.dnn`).  

---

## ✨ Features  
✔️ **Image-based Object Detection**: Detects and labels objects in static images.  
✔️ **Real-time Video Detection**: Identifies objects in a live video feed using a webcam.  
✔️ **MobileNet-SSD Model**: Lightweight deep learning model optimized for real-time applications.  
✔️ **Adjustable Confidence Threshold**: Filters out low-confidence detections to improve accuracy.  

---

## 🔧 Technologies Used  
- **Python** 🐍  
- **OpenCV** 🎥  
- **NumPy** 🔢  
- **MobileNet-SSD (Caffe framework)** 📦  

---

## 📥 Installation  
To run this project, install the required dependencies:  

```bash
pip install numpy opencv-python imutils

## 🚀 Usage
### 🎯 1. Image-based Object Detection  
Run the following command to detect objects in an image:  

```bash
python deep_learning_object_detection.py --image path/to/image.jpg --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel

### 📹 2. Real-Time Video Object Detection
To run real-time detection using a webcam:
