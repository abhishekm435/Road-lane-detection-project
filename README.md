# 🛣️ Road Lane Line Detection Project

## 🚗 Overview
This project implements a **road lane detection system** using **computer vision techniques** in Python. It is designed as part of an advanced **driver assistance system (ADAS)** to detect and highlight lane lines in real-time video feeds, helping enable **autonomous driving** and improve **road safety**.

---

## 📌 Features
- Detects **lane boundaries** from video frames using image processing techniques.
- Handles **various lighting** and **road conditions**.
- Performs **real-time lane tracking** from dashcam video.
- Can be extended to integrate with **autonomous vehicle control systems**.

---

## 🧰 Technologies Used
- **Python 3**
- **OpenCV**
- **NumPy**
- **Matplotlib** (for visualization)
- (Optional) **Scikit-learn** (for any ML-based enhancements)

---

## 🔬 Methodology
1. **Frame Extraction** from video.
2. **Preprocessing**:
   - Grayscale conversion
   - Gaussian Blur
   - Canny Edge Detection
3. **Region of Interest (ROI)** masking
4. **Hough Line Transform** to detect lane lines
5. **Line Averaging and Extrapolation** to draw stable lines
6. **Overlay detected lanes** on the original video

---

## 📂 Project Structure
road-lane-detection/
│
├── videos/ # Input video files
├── output/ # Output videos with lane overlay
├── lane_detection.py # Main script
├── utils.py # Helper functions
├── README.md # Project documentation
└── requirements.txt # List of required packages
