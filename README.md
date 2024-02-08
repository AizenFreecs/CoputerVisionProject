# Computer Vision Object Detection Project 🖥️👁️🚀

## Introduction

This project focuses on computer vision-based object detection, specifically targeting offensive hand gestures in images. Various models have been trained to accomplish this task, aiming to detect and classify offensive gestures accurately.

## The Dataset 📊🔍

The dataset utilized in this project has been meticulously curated to ensure diversity and robustness in model training. It comprises over 2000 images sourced from five different models, captured under various orientations, lighting conditions, and environmental settings. To enhance the dataset's quality and improve training efficiency, rigorous preprocessing techniques and various augmentations have been applied.

## The Models 🤖📋

Five different models have been employed in this project:

### YOLOv8 (You Only Look Once version 8) 🛠️🔍

YOLOv8 is a state-of-the-art object detection model known for its real-time processing capabilities and high accuracy. It operates by dividing the input image into a grid and predicting bounding boxes and class probabilities for each grid cell.

### YOLOv5 (You Only Look Once version 5) 📷🔍

YOLOv5 is an evolution of the YOLO series, focusing on simplicity and performance. It improves upon its predecessors by introducing a streamlined architecture while maintaining competitive accuracy and speed.

### EfficientDet 🌟🚀

EfficientDet is a family of object detection models developed by Google Research. These models are known for their efficiency in terms of parameter size and computational resources while achieving impressive accuracy.

### Faster R-CNN (Region-based Convolutional Neural Network) ⚡🔍

Faster R-CNN is a popular two-stage object detection model. It consists of a region proposal network (RPN) followed by a region-based CNN for object detection. Despite being slightly slower than some newer models, Faster R-CNN is known for its robust performance.

### RetinaNet 👁️🎯

RetinaNet is a single-stage object detection model designed to address the class imbalance issue inherent in many object detection datasets. It introduces a novel focal loss function that focuses training on hard examples, leading to improved accuracy across different object scales.

## Results 📈🔍

The evaluation of the trained models yielded promising results, with YOLOv8 exhibiting the best performance. It achieved a mean Average Precision (mAP) of 81 at a confidence threshold of 0.5, indicating the model's capability to accurately detect offensive hand gestures in images. Further analysis of model performance metrics and visualizations can be found in the project documentation.

---


