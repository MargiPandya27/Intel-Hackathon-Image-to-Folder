
# Object Detection and Categorization for Image and Video 


## Problem Statement
Imagine being able to effortlessly analyze and categorize vast collections of images and videos in a snap! With the power of computer vision, we can develop a cutting-edge model that accurately detects and categorizes different objects, providing us with invaluable insights and saving us hours of tedious manual work. From identifying objects' presence and location to classifying them into relevant categories, our model will revolutionize the way we approach image and video analysis. Say goodbye to the hassle of sifting through endless files and say hello to the future of efficient and automated image and video processing!

## **OUTPUT**: 
![Images without Segregation](https://github.com/MargiPandya27/Intel-Hackathon-Image-to-Folder/assets/117746681/ad6f7c69-31c8-4f86-ad18-6f8229bcfc9c)
Images stored in a folder without segregation.

![image](https://github.com/MargiPandya27/Intel-Hackathon-Image-to-Folder/assets/117746681/e82b42f0-0d15-46f0-ac3d-91fbb3509249)
Sorted images in the specific folders.

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
