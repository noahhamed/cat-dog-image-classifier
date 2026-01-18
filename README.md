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
## Screenshots

### Training Curves
<img width="751" height="685" alt="image" src="https://github.com/user-attachments/assets/48caa023-44f8-48ff-afe5-ab3798dfa0f2" />


### Test Predictions
 <img width="201" height="888" alt="image" src="https://github.com/user-attachments/assets/53f0e21f-33e7-4814-8797-a65e44d2a2e1" /> <img width="205" height="900" alt="image" src="https://github.com/user-attachments/assets/fb5214a9-1bdd-45d6-a754-0a0ee82ac2b4" />





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

