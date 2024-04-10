# YOLOv8-for-Object-Detection

## Overview

In this repository, I used YOLOv8 from ultralytics library to train with this [dataset](https://drive.google.com/file/d/1sX9qmlPY1SXwboz9qOzjyLrkzCwYoT31/view).

The dataset is a car detection folder including 371 images, splitting into 345 for training and 26 for testing.

The dataset folder contains one files and two folders: 
- val folder contains images folder and labels folder, which has 26 files for each. 
- train folder contains images folder and labels folder, which has 345 files for each. 
- data.yml file contains information about the dataset for model to load.

I also uploaded the training model weights and the cloning model from ultralytics. 

The model would make the prediction and then the visualize_bbox functions will show the results and the bounding boxes of the object.

## Outline
This project contains these processes: 
1. Load dataset 
2. Model training 
3. Model evaluation 
4. Prediction