# Cardiac-Detection-DeepLearning
This repository contains my implementation and assessment work for a deep learning-based cardiac detection task using chest X-ray images.
---

## 📌 Overview

This project is an overview of cardiac detection through medical x-rays using deep learning model.

Topics covered include:

- Medical image preprocessing
- Bounding box annotation handling
- Custom PyTorch Dataset creation
- Data augmentation for object localization
- Deep learning model training
- Model checkpointing and experiment logging

The dataset used is based on the RSNA Pneumonia Detection Challenge dataset with provided cardiac bounding box annotations.

---

## 🧪 Project Pipeline

### Preprocessing

The preprocessing notebook prepares the dataset for training by:

- Loading chest X-ray images and annotations
- Converting image data into `.npy` format for faster loading
- Organizing bounding box information
- Optimizing storage and preprocessing workflows

---

### Dataset 

A custom PyTorch `Dataset` is implemented to:

- Load X-ray images and corresponding cardiac bounding boxes
- Apply normalization and augmentation
- Perform synchronized image and bounding box transformations

Bounding box augmentation is implemented using `imgaug` to ensure spatial consistency during transformations.

---

### Model Training

The training notebook implements the deep learning pipeline using PyTorch Lightning.

The workflow includes:

- DataLoader creation
- Augmentation pipelines
- Training and validation loops
- Model checkpointing
- TensorBoard logging
- Bounding box visualization using OpenCV

---

## ⚙️ Technical Implementation

### Deep Learning Workflow

- Medical image preprocessing
- Bounding box regression pipeline
- Custom dataset and dataloader implementation
- Augmentation-aware localization training
- Model training and validation
- Experiment tracking and checkpoint saving

### Techniques Used

- Bounding Box Localization
- Data Augmentation
- Image Normalization
- PyTorch Dataset Engineering
- Deep Learning Model Training
- Experiment Logging and Checkpointing
