🧠 AI Object Detection in Google Colab
This project demonstrates object detection using a variety of pre-trained models from TensorFlow Hub. It provides a flexible framework to load, visualize, and test different object detection architectures (including EfficientDet, CenterNet, SSD, and Faster R-CNN) directly within Google Colab.

🚀 Features
Select from 30+ TensorFlow Hub object detection models

Clone and compile the TensorFlow Model Zoo via protobuf and setup.py

Load and preprocess custom images using PIL, NumPy, and Matplotlib

Run inference and visualize results using bounding boxes and class labels with visualization_utils

📦 Dependencies
TensorFlow 2.x

TensorFlow Hub

Protobuf Compiler (protoc)

PIL, NumPy, Matplotlib

TensorFlow Object Detection API (via models/research)

📁 Workflow
Clone TensorFlow’s Model Zoo

Compile .proto files with protoc

Install and initialize the Object Detection API

Load label maps (COCO dataset)

Upload and process images

Run detection and visualize output

🖼️ Example Output
Bounding boxes are rendered over uploaded images, showing object class and confidence score.
