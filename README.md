# Pressure injury detection and staging classification

This repository contains the script for training the pressure injury dataset with YOLOv4, which can detect the pressure injury and the staging level classification in a pressure injury image. 

## Getting started

### Input data

The pressure injury dataset consists of images from:

1. [Medetec Wound Database](http://www.medetec.co.uk/files/medetec-image-databases.html)

2. Google images
 
### Image annotation
 
We used [CVAT](https://cvat.org/) to perform the image annotation of the pressure injury dataset.

### Data Augmentation and spltting

We use [Roboflow](https://roboflow.ai) to perform the data augmentation, which is used for creating more images. We also used [Roboflow](https://roboflow.ai) to split the data into training, validation, and testing set.

## Andriod implementation

Download this repository to your local machine and open it in Andriod Studio as
a project, and build it by "Build APK(s)".
