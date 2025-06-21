# Brain Tumor Segmentation using YOLOv11 and SAM2 (Google Colab Version)
This project implements an end-to-end pipeline for brain tumor detection and segmentation using deep learning models YOLOv11 (mocked with YOLOv8) and SAM2 (Segment Anything Model version 2). It is designed to run on Google Colab for easy experimentation and deployment.

Features
Data Upload and Preprocessing:
Upload and extract brain MRI dataset, with automatic resizing and normalization for model input.

Custom Dataset Loader:
PyTorch Dataset class for loading brain tumor images from training and testing directories.

Tumor Detection with YOLO:
Uses a pretrained YOLOv8 model for object detection to localize tumor regions in MRI scans.

Tumor Segmentation with SAM2:
Utilizes the Segment Anything Model to accurately segment tumor boundaries within detected regions.

Visualization:
Displays bounding boxes around tumors and overlays segmentation masks on input images for easy interpretation.

Modular Pipeline:
Separate functions for detection, segmentation, and visualization, enabling flexibility and easy extension.

Deployment-Ready:
Built-in capability to run in a cloud environment (Google Colab) for quick prototyping and testing.

How to Use
Install required libraries: ultralytics, segment-anything, opencv-python, matplotlib.

Upload your dataset ZIP file containing MRI images.

Upload the SAM model checkpoint file (.pth).

Run the pipeline to perform detection and segmentation on test images.

Visualize the results directly in the notebook.

Requirements
Python 3.7+

PyTorch

Google Colab environment recommended for GPU acceleration.

Project Structure
Dataset: Brain MRI images in training/testing folders.

Models: YOLOv8 pretrained weights and SAM2 checkpoint.

Scripts: Dataset loading, detection, segmentation, and visualization.

Notes
YOLOv11 is currently mocked using YOLOv8 due to availability.

Adjust dataset paths as needed to match your folder structure.

Visualization colors: green bounding boxes, red segmentation masks.

