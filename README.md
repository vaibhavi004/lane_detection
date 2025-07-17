# 🛣️ PathPilot: OpenCV-Based Lane Detection for Safe Navigation

An efficient lane detection system using traditional computer vision techniques such as Canny Edge Detection and Hough Transform. Built with OpenCV, this project aims to improve road safety by providing real-time lane detection under various environmental conditions, laying the foundation for autonomous vehicle navigation and ADAS applications.

---


## 🧠 Abstract

This project focuses on real-time lane detection using OpenCV to assist with autonomous driving and ADAS functionality. The system uses image preprocessing, Canny edge detection, region of interest masking, and Hough line transforms to detect road lanes in videos under varying lighting and weather conditions. The model achieves a performance of 63.66 FPS and 92% accuracy, making it viable for real-time applications.

---

## 🌟 Features

- Real-time lane detection (63+ FPS)
- Works in varying conditions: daytime, nighttime, fog
- Canny Edge Detection and Hough Transform
- Region of Interest (ROI) filtering for precision
- Pre-recorded video processing
- Visual lane overlay on video output

---

## 🛠️ System Overview

- **Input:** Pre-recorded road video
- **Image Preprocessing:** Grayscale + Gaussian Blur
- **Edge Detection:** Canny algorithm
- **Lane Isolation:** Region of Interest masking
- **Line Detection:** Hough Transform
- **Post-Processing:** Line averaging, overlay rendering

---

## 💻 Technologies Used

- Python 3
- OpenCV
- Numpy
- Matplotlib (for visualizations)

---

## 🧪 Methodology

| Step                  | Technique Used           | Purpose                                  |
|-----------------------|--------------------------|-------------------------------------------|
| Noise Reduction       | Gaussian Blur            | Remove noise for smoother edge detection |
| Edge Detection        | Canny Edge Detector      | Detect road lane boundaries              |
| ROI Masking           | Polygonal Masking        | Focus on lane region                     |
| Line Detection        | Hough Line Transform     | Detect and classify straight lines       |
| Line Smoothing        | Linear Regression        | Average line data and smooth edges       |
| Line Extension        | Geometry Calculations    | Ensure full lane display in frame        |

---
<img width="1046" height="658" alt="Screenshot 2025-07-17 182501" src="https://github.com/user-attachments/assets/1845065a-cd0a-48a8-ad51-0609d9d6cff1" />

## ✅ Performance

| Metric        | Value   | Description                                    |
|---------------|---------|------------------------------------------------|
| Accuracy      | 92%     | Correctly identified lane lines                |
| Precision     | 0.80    | Detection correctness                         |
| F1 Score      | 0.86    | Balance between precision and recall           |
| FPS           | 63.66   | Real-time performance                          |
| RMSE          | 7.66    | Deviation from ground truth lane lines         |

---

## 🚀 Applications

- Advanced Driver Assistance Systems (ADAS)
- Autonomous vehicle navigation
- Lane departure warning systems
- Smart traffic analytics

---

## 🔮 Future Work

- Improve performance in foggy/rainy conditions
- Integrate with object detection for ADAS
- Real-time dashboard display using OpenCV GUI
- Transition to deep learning models for curved road detection
- Add lane prediction with temporal tracking

---

