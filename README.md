# Colorectal Cancer Detection Using Deep Learning

## Overview

Colorectal cancer is a major global health concern, and early detection is essential for improving patient outcomes. This project explores deep learning-based colorectal cancer detection using histopathological images and Convolutional Neural Networks (CNNs).

The project uses the **EBHI-Seg dataset**, comprising 4,456+ histopathological images, to develop an automated image-classification approach for distinguishing cancerous and non-cancerous tissue. The work includes image preprocessing, model training, and classification, with the aim of supporting efficient and consistent medical image analysis.

## Dataset

- **Dataset:** EBHI-Seg
- **Data type:** Histopathological images
- **Dataset size:** 4,456+ images
- **Segmentation annotations:** Ground-truth segmentation information for 2,228+ images

The dataset is used to explore deep learning techniques for identifying patterns associated with colorectal cancer in histopathological images.

## Objectives

- Develop a CNN-based deep learning model for colorectal cancer detection.
- Preprocess histopathological images for model training and evaluation.
- Train and evaluate a model using labelled medical image data.
- Classify images into cancerous and non-cancerous categories.
- Explore the potential of automated image analysis to support early detection.

## Methodology

1. **Dataset Preparation:** Organise the EBHI-Seg images for model development.
2. **Image Preprocessing:** Resize and transform images into the appropriate input format.
3. **Model Training:** Train the deep learning model on the prepared dataset.
4. **Image Classification:** Generate predictions for input histopathological images.
5. **Result Presentation:** Display classification results through a web-based interface.

## System Modules

### 1. System Module
- Dataset preparation and organisation
- Image preprocessing
- Deep learning model training
- Medical image classification

### 2. User Module
- Upload an image for analysis
- View the predicted classification result

## Technology Stack

- **Programming Language:** Python
- **Deep Learning:** Convolutional Neural Networks (CNNs), MobileNetV3
- **Backend:** Flask
- **Frontend:** HTML, CSS, Bootstrap, JavaScript
- **Libraries:** NumPy, Pandas
- **Development Environment:** PyCharm

## Key Outcomes

The project explores automated colorectal cancer image classification using deep learning. According to the project results documented in my resume, the model achieved **95% classification accuracy** on the EBHI-Seg dataset, outperforming the baseline by 12%.

## Applications

- Histopathological image classification
- Research into AI-assisted cancer detection
- Exploration of deep learning for medical image analysis

## Limitations

This project is an academic research prototype. Its predictions should not be used as a standalone clinical diagnosis. Further validation on independent datasets and clinical assessment would be required before any real-world medical use.

---

**Project Domain:** Deep Learning, Computer Vision, Medical Image Analysis, and Healthcare AI.
