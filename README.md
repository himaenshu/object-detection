---

# 🌾 Crop and Weed Classification using Object Detection

This project focuses on identifying and classifying crops and weeds using object detection techniques. The goal is to assist in automated weed management for precision agriculture, reducing manual labor and improving crop yield.

## 📌 Project Overview

- **Problem**: Manual weed detection is time-consuming and labor-intensive.
- **Solution**: Deploy an object detection model to distinguish between crops and weeds in field images.
- **Method**: Fine-tuned YOLOv8 (You Only Look Once) model on a labeled dataset of crops and weeds.

## 🧠 Model Details

- **Architecture**: YOLOv8 (ultralytics)
- **Framework**: TensorFlow / PyTorch (as used)
- **Classes**: 
  - `crop`
  - `weed`

## 📁 Dataset
- Link - https://www.kaggle.com/datasets/himanshuraj56256/dataset
- 
- Structured in YOLO format:
  ```
  dataset/
  ├── images/
  │   ├── train/
  │   └── val/
  ├── labels/
  │   ├── train/
  │   └── val/
  └── data.yaml
  ```
- Contains annotated images with bounding boxes for crops and weeds.

## 🚀 Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/himaenshuu/crop_weed_classification.git
   cd crop_weed_classification
   ```

## 📊 Evaluation Metrics

- Precision, Recall, mAP (mean Average Precision)
- Real-time inference speed (FPS)

## 📦 Outputs

- Trained weights
- Detection results with bounding boxes
- Training logs and metrics

## 🧑‍🌾 Applications

- Smart farming
- Autonomous weeding robots
- Agricultural monitoring systems
