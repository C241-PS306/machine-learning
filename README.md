# Machine Learning Team - WearShare
## Project Overview
Our capstone project focuses on identifying decent and indecent clothing, specifically shirts with holes, using machine learning techniques. The project includes data collection, data enhancement, model building, comparison and evaluation, and deployment stages. 

## Table of Contents
- [Data Collection](#data-collection)
- [Data Enhancement](#data-enhancement)
- [Model Building](#model-building)
- [Comparison & Evaluation](#comparison--evaluation)
- [Deployment](#deployment)


## Data Collection
We collected images from various sources:
- **Indecent Clothing**: Google Images, Roboflow, and Pinterest.
- **Decent Clothing**: Kaggle.

## Data Enhancement
We enhanced the dataset using manual augmentation techniques via Roboflow. These techniques included:
- Rotating images
- Flipping images
- Other augmentations to increase variety

**Note**: We did not convert the images to grayscale.

## Model Building
We built two types of models:
1. **Unpretrained Model**: A simple Convolutional Neural Network (CNN).
2. **Pretrained Models**: 
   - MobileNetV2
   - InceptionV3

## Comparison & Evaluation
We compared the performance of unpretrained and pretrained models:
1. The pretrained models showed better accuracy compared to the unpretrained model.
2. Among the pretrained models, MobileNetV2 outperformed InceptionV3.

## Deployment
We deployed the MobileNetV2 model by converting it into TensorFlow.js format (.json and .bin), enabling the Cloud Computing (CC) team to create an API for the Mobile Development (MD) team.
