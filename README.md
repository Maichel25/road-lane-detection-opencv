# 🚗 Road Lane Detection using OpenCV

A classical computer vision project for detecting road lane markings in images and videos using OpenCV and NumPy.

This project implements a full lane detection pipeline commonly used in introductory autonomous driving systems.

---

## ✨ Features

- Grayscale preprocessing
- Gaussian blur noise reduction
- Canny edge detection
- Region of Interest (ROI) masking
- Hough Line Transform
- Lane overlay visualization
- Real-time video processing
- Parameter tuning visualization

---

## 🧠 Techniques Used

| Component | Technique |
|---|---|
| Preprocessing | Grayscale + Gaussian Blur |
| Edge Detection | Canny Edge Detector |
| ROI Extraction | Polygon Masking |
| Lane Detection | Probabilistic Hough Transform |
| Visualization | OpenCV Drawing Functions |

---

## 📂 Project Structure

```bash
road-lane-detection-opencv/
│
├── notebooks/
│   └── road_lane_detection.ipynb
│
├── images/
│   ├── test_image.jpg
│   └── results/
│
├── videos/
│   ├── input.mp4
│   └── output/
│
├── src/
│   ├── preprocessing.py
│   ├── edge_detection.py
│   ├── roi.py
│   ├── lane_detection.py
│   └── video_pipeline.py
│
├── requirements.txt
├── README.md
├── LICENSE
└── .gitignore
