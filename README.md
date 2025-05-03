# Yolov5-car-object-detection
Detects cars in real-time  using the YOLOv5 deep learning architecture

This project implements a real-time car detection system using the YOLOv5 deep learning architecture.

It detects and localizes vehicles in images and video streams, demonstrating applications in traffic analysis, surveillance, and autonomous vehicles.

## Technologies Used
- **YOLOv5** (Ultralytics)
- **Python**
- **OpenCV**
- **PyTorch**

## Dataset
- Custom dataset with car images and annotated bounding boxes.
- Format: YOLO format (`.txt` files for bounding boxes).
- Optionally compatible with subsets of the COCO dataset.

## Features
- Real-time object detection with bounding boxes and confidence scores.
- Support for training and testing on custom datasets.
- Modular pipeline for easy dataset updates or retraining.

## 🛠️ Usage

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/yolo-car-object-detection.git
cd yolo-car-object-detection
