# Driver Drowsiness Detection System

## Project Overview
This project implements a real-time drowsiness detection system using a deep learning model based on the YOLOv5 architecture. It detects and classifies driver's eye and head positions to determine whether the driver is drowsy or awake, enhancing road safety.

## Features
- Real-time drowsiness detection using webcam feed.
- Uses YOLOv5 for object detection, specifically trained to recognize human eyes and face orientation.
- Bounding boxes indicating eye states (open or closed) and head position.
- Custom trained model to accurately detect specific user characteristics.

## Installation
To set up this project, follow the steps below:
1. **Run directly on Colab environment:**
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sun-of-a-beach/Quantium-Virtual-Internship---Retail-Strategy-and-Analytics-Task-1/blob/main/Quantium_task_1_data.ipynb)

## Usage
There are model weights to try out or you can train your own model. Just upload the model weights to Colab and change the weights path. Ensure your webcam is enabled and properly configured to allow real-time detection.

## Model Training
Trained Yolov5 model from [ultralytics](https://github.com/ultralytics/yolov5)
Dataset used: 44 images awake and drowsy images capturing various eye states and head positions.
Annotations: Labels indicating eye and head positions with bounding boxes. For this I have used [LabelImg](https://github.com/tzutalin/labelImg)<br>
Training procedure: Trained for 500 epochs:

<br>![Real time detection via Web-cam in Colab]('model training/results.png')

## Detection:
<br>![Real time detection via Web-cam in Colab](detection_images/detection_2.png)


