# Medical MNIST Classification using VGG16/VGG19 and Transfer Learning

## Overview

This repository implements a classification task on the Medical MNIST dataset using transfer learning with VGG16 or VGG19 networks. 

## Dataset
The dataset includes medical images from six classes:
- Abdomen CT
- Breast MRI
- Chest CT
- CXR
- Hand
- Head CT

## Transfer Learning

Transfer learning utilizes pre-trained VGG16/VGG19 networks, originally trained on ImageNet, for classifying medical images into the specified six classes. The end layers of these networks are removed, and new layers are added for the custom classification task.

## Implementation

The code uses Pytorch for the transfer learning process. 
