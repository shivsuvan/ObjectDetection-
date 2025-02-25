
# 🏆 Real-Time Object Detection using MobileNet-SSD  

## 📌 Overview  
This project implements **real-time object detection** using the **MobileNet-SSD** model in the **Caffe deep learning framework**.  
It can detect multiple objects in images and live video streams using OpenCV’s deep learning module (`cv2.dnn`).  

---

## ✨ Features  
- **Image-based Object Detection**: Detects and labels objects in static images.  
- **Real-time Video Detection**: Identifies objects in a live video feed using a webcam.  
- **MobileNet-SSD Model**: Lightweight deep learning model optimized for real-time applications.  
- **Adjustable Confidence Threshold**: Filters out low-confidence detections to improve accuracy.  

---

## 🔧 Technologies Used  
- **Python** 🐍  
- **OpenCV** 🎥  
- **NumPy** 🔢  
- **MobileNet-SSD (Caffe framework)** 🛋️  

---

## 👅 Installation  
To run this project, install the required dependencies:  

```bash
pip install numpy opencv-python imutils
```

---

## 🚀 Usage  

### 🎯 1. Image-based Object Detection  
Run the following command to detect objects in an image:  

```bash
python deep_learning_object_detection.py --image path/to/image.jpg --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel
```

### 📹 2. Real-Time Video Object Detection  
To run real-time detection using a webcam:  

```bash
python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel
```

---

## 📂 Model and Dataset  

- **Model**: The project uses a **pre-trained MobileNet-SSD model** for fast object detection.  
- **Classes Detected**:  
  The model can detect **20 different object categories**, including:  
  - 🏃 Person  
  - 🚗 Car  
  - 🐶 Dog  
  - 🚲 Bicycle  
  - 🪑 Chair  
  - 🍾 Bottle  
  - 🚌 Bus  
  - And many more...  

---

## 🗄 Example Output  

After running the scripts, the detected objects will be displayed with bounding boxes and labels in real time.  
 

---

## 🔮 Future Enhancements  

- Extend support for **custom-trained object detection models**.  
- Optimize performance for **mobile and embedded devices**.  
- Implement **tracking** to follow detected objects across frames.  

---

## 📝 License  

This project is for educational purposes. You are free to modify and use it as needed.  

📌 **Created with ❤️ by Shivsuvan  
```

