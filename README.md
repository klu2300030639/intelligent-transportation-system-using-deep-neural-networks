# Intelligent Transportation System Using Deep Neural Networks

## Overview
This project presents an end-to-end deep learning pipeline for intelligent transportation systems using the YOLOv8s model.

The system detects and classifies traffic objects such as:
- Cars
- Buses
- Trucks
- Pedestrians
- Traffic Lights
- Traffic Signs

The model is trained on the BDD100K dataset and is designed for real-time traffic monitoring and smart city applications.

## Model Details
- Model: YOLOv8s (Small Variant)
- Dataset: BDD100K
- Classes: 6
- mAP@0.5: 0.41
- mAP@0.5:0.95: 0.28
- FPS: 28–32

## Applications
- Intelligent Transportation Systems
- Traffic Monitoring
- Smart Cities
- Autonomous Driving
- Road Safety Analysis

## Conference Publication
Accepted (Provisional) at AI-PTIS 2026.

## Project Results

### Training Results
![Training Results](training_results.png)

### Confusion Matrix
![Confusion Matrix](confusion_matrix.png)

### Normalized Confusion Matrix
![Normalized Confusion Matrix](normalized_confusion_matrix.png)

### Precision-Recall Curve
![Precision Recall Curve](precision_recall_curve.png)

### F1 Score Curve
![F1 Score Curve](f1_score_curve.png)

### Traffic Detection Output
![Traffic Detection Output](traffic_detection_output.jpg)

### Dense Traffic Detection Output
![Dense Traffic Detection Output](dense_traffic_detection_output.jpg)
