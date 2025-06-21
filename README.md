# 🧠 Brain Tumor Segmentation using YOLOv11 and SAM2 (Google Colab Version) 🚀
This project implements an end-to-end pipeline for brain tumor detection and segmentation using deep learning models YOLOv11 (mocked with YOLOv8) and SAM2 (Segment Anything Model v2). Designed for easy use on Google Colab for fast experimentation! 💻✨

🔥 Features
📂 Data Upload & Preprocessing
Upload your brain MRI dataset ZIP file, with automatic extraction, resizing, and normalization for model input.

📚 Custom Dataset Loader
PyTorch Dataset class for loading brain tumor images from training & testing folders.

🎯 Tumor Detection with YOLO
Pretrained YOLOv8 model detects tumor regions in MRI scans with high accuracy.

✂️ Tumor Segmentation with SAM2
Segment Anything Model precisely segments tumor boundaries within detected regions.

👁️ Visualization
View green bounding boxes around tumors and red overlays for segmentation masks.

⚙️ Modular Pipeline
Clear, reusable functions for detection, segmentation, and visualization.

☁️ Cloud Ready
Runs smoothly on Google Colab with GPU support for quick prototyping.

🚀 How to Use
Run the cell to install required libraries: ultralytics, segment-anything, opencv-python, matplotlib.

Upload your MRI dataset ZIP file 🗂️.

Upload your SAM model checkpoint .pth file 🧩.

Run the pipeline to detect and segment tumors in test images 🎥.

Visualize results instantly inside the notebook! 🎨

🛠️ Requirements
Python 3.7+ 🐍

PyTorch framework 🔥

Google Colab (recommended for GPU acceleration) ☁️💻

🗂️ Project Structure
Dataset: Brain MRI images in /Training and /Testing folders.

Models: YOLOv8 pretrained weights + SAM2 checkpoint.

Scripts: Dataset loader, detection, segmentation, visualization.

⚠️ Notes
YOLOv11 is currently mocked with YOLOv8 due to availability.

Adjust dataset paths if your folder structure differs 🛠️.

Visualization colors:

🟢 Green boxes = Tumor detections

🔴 Red masks = Tumor segmentations



