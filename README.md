
# Object Detection and Categorization for Image and Video 


## Problem Statement
The task is to develop a computer vision model to detect and categorize
objects in images and videos stored on a laptop. The model should be able
to accurately identify the presence and location of different objects within
the images and videos and classify them into relevant categories.
The categories could be predefined or learned from the data. The goal is to
provide an efficient and automated way to analyze and categorize extensive
collections of images and videos.


## Dataset

Download Dataset: (https://www.kaggle.com/code/gcdatkin/marvel-character-image-classification/input)


## Pre-Requisites(prefered)
**Softwares**:
1. OpenAPI,
2. Google Colab/Jupyter Notebook


**Packages**:
1. Python >= 3.5
2. Torch >= 1.8.1
3. Torchvision >= 0.9.1


**NOTE**:
Make sure that dataset is as specified. Put the `.yaml` file into yolov5 folder after cloning it. Change the location in the avenger.yaml according to your dataset location.

### Training on custom dataset 
1. Form a dataset folder 
2. Make a folder named **images** and **label** 
3. Upload the files.
4. Perform Augmentation using `Augmentation.ipynb`
5. Define paths and class labels in `.yaml` file.


## References:

Augmentation:

https://www.learnpytorch.io/04_pytorch_custom_datasets/

Object Detection

https://github.com/nicknochnack/YOLO-Drowsiness-Detection
