# Lane and Car Detection Project

This project implements a video processing pipeline that detects lane lines and cars in video footage. It combines traditional computer vision techniques for lane detection with the YOLOv8 deep learning model for real-time car detection and distance estimation.

---

## Features

- **Lane Detection:** Uses Canny edge detection, region masking, and Hough Transform to detect and highlight lane lines on the road.
- **Car Detection:** Utilizes the YOLOv8 model to detect cars in the video frames.
- **Distance Estimation:** Estimates the approximate distance to detected cars based on bounding box size.
- **Real-time Video Processing:** Processes video frames, overlays lane and car detections, and displays the result in a window.
- **Configurable for different video inputs and resolutions.**

---

## Requirements

- Python 3.8+
- OpenCV (`cv2`)
- NumPy
- Ultralytics YOLOv8 (`ultralytics` package)
- A pre-trained YOLOv8 model (`yolov8n.pt` recommended)

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/adityapachkor7573/Lane-and-Car-Detection-Project.git
   cd Lane_Detection-main
