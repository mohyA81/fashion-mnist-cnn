# Fashion-MNIST Image Classification with CNN

## Overview

This project uses a Convolutional Neural Network (CNN) built with PyTorch to classify images of clothing from the Fashion-MNIST dataset.

The dataset contains 70,000 grayscale images across 10 clothing categories. Each image is 28 × 28 pixels.

## Technologies

- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Model Architecture

The CNN consists of:
- Two convolutional layers
- ReLU activation functions
- Two max-pooling layers
- A fully connected classifier

## Results

- **Test Accuracy:** 91.73%
- **Test Loss:** 0.2694

The model was evaluated using a confusion matrix, a classification report, and sample predictions.

## Project Structure

- `Fashion-MNIST.ipynb` — Data preparation, model training, evaluation, and visualizations
- `fashion_cnn.pth` — Saved model weights
- `data/` — Fashion-MNIST dataset files

## How to Run

1. Install Python and the required libraries.
2. Open `Fashion-MNIST.ipynb` in Jupyter Notebook.
3. Run the notebook cells in order.

The notebook downloads the dataset automatically if it is not already available.

## Dataset

Fashion-MNIST is a dataset of grayscale clothing images provided through Torchvision.

Dataset information: https://github.com/zalandoresearch/fashion-mnist
