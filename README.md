# Garbage Classification Project: 12 Classes

This project focuses on building a Convolutional Neural Network (CNN) to classify garbage into 12 categories, promoting environmental awareness and improving waste sorting systems.

## Features
- **12 Garbage Classes**: Battery, Biological, Brown Glass, Cardboard, Clothes, Green Glass, Metal, Paper, Plastic, Shoes, Trash, White Glass.
- **Image Preprocessing**: Data augmentation and resizing to 150x150 pixels.
- **Deep Learning Model**: CNN with dropout and L2 regularization for enhanced generalization.
- **Evaluation Metrics**: Accuracy, loss, and F1-score.

## Requirements
- Python 3.x
- TensorFlow/Keras
- NumPy
- Matplotlib

## Usage
1. Clone the repository.
2. Prepare the dataset using `ImageDataGenerator`.
3. Train the model with:
   ```bash
   python train.py
