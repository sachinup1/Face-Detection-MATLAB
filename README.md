# Face Detection using MATLAB

## 📌 Overview

This project demonstrates a basic face detection system built using MATLAB.
The model detects human faces in an image and draws bounding boxes with confidence scores.

---

## ⚙️ Methodology

* ROI labeling using MATLAB Image Labeler
* Dataset creation with manually annotated faces
* Training using ACF (Aggregate Channel Features) Object Detector
* Detection using MATLAB `detect()` function

---

## 🛠️ Technologies Used

* MATLAB
* Computer Vision Toolbox
* ACF Object Detector

---

## 📂 Project Workflow

1. Label images using Image Labeler (ROI)
2. Generate training data
3. Train detector using `trainACFObjectDetector`
4. Detect faces using trained model

---

## 📊 Results

The model successfully detects faces in images and displays:

* Bounding boxes
* Confidence scores

(Add output images here)

---

## ▶️ How to Run

1. Open MATLAB
2. Run `finalpro.m`
3. Input image will be processed
4. Output will display detected faces

---

## 🤝 Contributors

* Sachin Upadhyay
* Nenavath Prakash

---

## 🚀 Future Improvements

* Upgrade to CNN-based models
* Use YOLO or SSD for better accuracy
* Real-time face detection

---

## 📌 Note

This is a basic implementation intended for learning computer vision concepts.

