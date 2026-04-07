# Challenge 1: Image Repair + Style Transformation

This project demonstrates image degradation, image reconstruction, and style transformation using a small flower dataset.

## Dataset
A small subset of 30 flower images was used:
- 10 daisy
- 10 rose
- 10 sunflower

## Workflow
1. Load and resize images
2. Apply degradation using Gaussian blur and Gaussian noise
3. Train a convolutional autoencoder to reconstruct the original images
4. Apply a cartoon style transformation to the repaired outputs

## Outputs
- Degraded input images
- Repaired images
- Stylized images

## Tools Used
- Python
- OpenCV
- TensorFlow / Keras
- Google Colab
