# Face Mask Detection Using CNN

A deep learning project to detect whether a person is wearing a face mask, leveraging Convolutional Neural Networks (CNN) with Python and TensorFlow. The dataset is sourced from Kaggle.

## Project Overview

This project implements a CNN to classify images as **with mask** or **without mask**. It processes the Face Mask dataset, trains a deep learning model, and offers predictions on new images.

## Dataset

- **Classes:** `with_mask`, `without_mask`
- **Total images:** 7,553

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- OpenCV (`cv2`)
- Pillow
- scikit-learn
- matplotlib
- Kaggle API

**Install all dependencies:**
pip install tensorflow keras numpy opencv-python pillow scikit-learn matplotlib kaggle


## Sample Results

- The CNN achieves about **91% test accuracy** after 5 epochs of training.
- Images are accurately classified as "wearing a mask" or "not wearing a mask".


