# Mask_Detection
Individual Project

# Mask Detection using YOLOv8

This project focuses on building a mask detection system using YOLOv8, a state-of-the-art object detection model, to detect whether people are wearing masks properly, improperly, or not wearing them at all. The project utilizes the Ultralytics library for training and inference.

## Dataset
The dataset used for training and evaluation can be downloaded from the following link:
[Mask Detection Dataset](https://drive.google.com/drive/folders/1aAXDTl5kMPKAHE08WKGP2PifIdc21-ZG)

## Requirements
Ensure you have the following dependencies installed before running the code:
- Ultralytics library: `pip install ultralytics`
- OpenCV: `pip install opencv-python`

## YOLOv8
The YOLOv8 model is utilized for object detection tasks in this project. YOLOv8 is implemented and managed by Ultralytics, providing efficient and accurate object detection capabilities.

### Resources:
- [Ultralytics GitHub](https://github.com/ultralytics/ultralytics)
- [Ultralytics Documentation](https://docs.ultralytics.com/)

## Usage
1. **Dataset Preparation**: Organize your dataset into a folder structure compatible with YOLOv8 requirements.
2. **Training**: Train the YOLOv8 model using the provided dataset. Adjust training parameters as necessary.
3. **Evaluation**: Evaluate the trained model's performance using validation data. Metrics such as mAP (mean Average Precision) are computed.
4. **Inference**: Perform mask detection on new images using the trained model.
