# Cat & Dog Image Classifier (TensorFlow / Keras)

A **convolutional neural network (CNN)** built with **TensorFlow 2.x** and **Keras** to classify images as **cat** or **dog**.  
Achieved **~76% accuracy** on a held-out test set.

## Overview
This notebook covers an end-to-end image classification pipeline:
- Load and preprocess image datasets (train/validation/test)
- Apply **data augmentation** to reduce overfitting
- Build and train a CNN using the Keras **Sequential** API
- Evaluate performance using accuracy/loss curves
- Generate probability-based predictions on unseen test images

## Skills Demonstrated
**Deep Learning**
- CNN architecture design (Conv2D + MaxPooling blocks)
- Binary classification (sigmoid output)
- Training setup (Adam optimizer, binary cross-entropy loss)
- Regularization with **Dropout**

**Data & Evaluation**
- Image normalization (rescaling 0–255 → 0–1)
- Data augmentation (rotation, shifts, zoom, flips, etc.)
- Train/validation monitoring
- Interpreting prediction probabilities and model accuracy

## Tech Stack
- **Python**
- **TensorFlow 2.x**
- **Keras**
- NumPy
- Matplotlib

## Files
- `cat_dog_classifier.ipynb` — Full training + evaluation notebook

## How to Run
1. Open `cat_dog_classifier.ipynb` in Google Colab
2. Click **Runtime → Run all**


## Notes
For faster training, enable **GPU** in Colab:
Runtime → Change runtime type → Hardware accelerator → GPU

