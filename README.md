# YOLOv8 for Object Detection

## Overview
This repository focuses on utilizing YOLOv8 from the Ultralytics library to train an object detection model with a specific dataset.

### Dataset Details:
- Dataset: Car detection folder
- Images: 371 images
- Split: 345 for training, 26 for testing
- Folder Structure:
    - val: Contains images and labels folders (26 files each)
    - train: Contains images and labels folders (345 files each)
- data.yml: File containing dataset information for model loading
Additionally, the repository includes uploaded training model weights and a cloned model from Ultralytics.

The model makes predictions, and the visualize_bbox function displays the results along with bounding boxes of the detected objects.

## Outline
This project encompasses the following processes:

1. Load dataset
2. Model training
3. Model evaluation
4. Prediction

Feel free to explore the repository to understand the implementation and results of YOLOv8 for object detection with the provided dataset.


