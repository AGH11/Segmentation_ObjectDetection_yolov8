```markdown
# YOLOv8 Object Detection Notebooks

This repository contains Jupyter Notebooks for object detection tasks using YOLOv8.

## Installation

To run these notebooks, please install the required dependencies:

```bash
pip install -r requirements.txt
pip install ultralytics
pip install Ipython
pip install roboflow
```

## Cloning YOLOv8 Repository

Clone the YOLOv8 GitHub repository using the following link:

[YOLOv8 GitHub Repository](https://github.com/ultralytics/ultralytics)

## Downloading the Football Player Detection Dataset

To download the 'football-player-detection' dataset, please visit the following link:

[Football Player Detection Dataset](https://universe.roboflow.com/bronkscottema/football-player-detection/dataset/3/download)

## Notebooks Description

### 1. Segmentation_yolov8.ipynb

This notebook demonstrates the usage of YOLOv8 for segmentation and detection tasks. It performs the following actions:

- Segmentation of objects in an image using YOLOv8
- Downloading a dataset from Roboflow for football player detection
- Training YOLOv8 on the downloaded dataset
- Validating the trained model
- Performing object detection on test images from the dataset

### 2. ObjectDetection_yolov8.ipynb

This notebook focuses on object detection using YOLOv8. It includes the following:

- Detection of objects in an image using YOLOv8
- Displaying the detected objects on the input image

## Folder Structure

The repository structure contains the following:

- `data` directory: Contains input images and videos.
- Detected images and videos generated from the notebooks are available in the main folder.
- `football-player segmented photos` directory: Example of football-player segmented photos.
## Usage

1. Clone the YOLOv8 repository.
2. Download the football player detection dataset.
3. Install the necessary dependencies.
4. Run the notebooks to perform object detection and segmentation tasks using YOLOv8.

Feel free to explore and modify the provided notebooks as needed.
