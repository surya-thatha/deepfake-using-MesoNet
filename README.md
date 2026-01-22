# Deepfake-using-MesoNet
Project Overview

Deepfakes are manipulated media created using deep learning techniques that can replace or alter faces in videos and images. This project focuses on detecting deepfake images using MesoNet, a lightweight Convolutional Neural Network (CNN) designed specifically for identifying deepfake artifacts.

The system classifies input images as REAL or FAKE based on learned visual patterns.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Objectives

Detect deepfake images accurately
Implement and train the MesoNet architecture
Classify images into real or fake
Provide a simple and efficient deepfake detection pipeline
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Model Used – MesoNet

MesoNet is a CNN architecture designed to:
Capture mesoscopic features in images
Detect inconsistencies introduced by deepfake generation
Work efficiently with fewer parameters

Key Features:
4 convolutional layers
Batch normalization
Max pooling
Fully connected layers
Sigmoid activation for binary classification
![WhatsApp Image 2025-12-14 at 08 00 16_6dd06568](https://github.com/user-attachments/assets/0baae317-7765-4b54-a228-4bf0c635e166)

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
The dataset consists of:
Real images
Fake (deepfake) images
Images are organized as:

dataset/
├── train/
│   ├── real/
│   └── fake/
├── validation/
│   ├── real/
│   └── fake/


You may use datasets such as:
FaceForensics++
DeepFake Detection Challenge (DFDC)
UADFV
# deepfake-using-MesoNet
