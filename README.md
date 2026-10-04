# Handwritten Digit Classifier

## About the Project

This project uses a Neural Network built with PyTorch to recognize handwritten digits from 0 to 9.

The model is trained using the MNIST dataset.

## Dataset

The MNIST dataset contains:

- 60,000 training images
- 10,000 testing images
- Each image is 28 × 28 pixels
- Images contain handwritten digits from 0 to 9

## Model Architecture

The neural network contains:

- Flatten layer
- Linear layer: 784 → 128
- ReLU activation
- Linear layer: 128 → 10

## Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib
- Jupyter Notebook

## Training

The model was trained using:

- Loss Function: Cross Entropy Loss
- Optimizer: Adam
- Learning Rate: 0.001
- Epochs: 5
- Batch Size: 64

## Results

The trained model achieved:

**97.44% Test Accuracy**

The model was also tested on sample handwritten digits and successfully predicted the displayed examples.

## Project Workflow

1. Load the MNIST dataset
2. Convert images into tensors
3. Create DataLoaders
4. Build the neural network
5. Move the model to GPU when available
6. Train the model
7. Evaluate the model
8. Visualize predictions
9. Save the trained model

## Project Files

- `handwritten_digit_classifier.ipynb` — Complete Jupyter Notebook
- `digit_classifier.pth` — Trained PyTorch model
- `README.md` — Project documentation

## Future Improvements

- Build a graphical interface
- Allow users to draw a digit and classify it
- Improve the model using Convolutional Neural Networks (CNN)
- Deploy the model as a web application