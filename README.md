# MNIST Classifier

This repository contains a simple PyTorch implementation to train and evaluate a neural network on the MNIST handwritten digits dataset

## Features
Loads and preprocesses the MNIST dataset automatically
Defines a simple fully connected neural network for digit classification
Trains the model using mini-batch gradient descent (Adam optimizer)
Evaluates test accuracy and plots the training loss curve
Saves the trained model for future use

## Instructions

1. Clone this repository:
git clone https://github.com/payu-witta/MNIT-Classifier.git

2. Navigate into the project folder:
cd MNIST-CLassifier

3. Install the required Python Library:
pip install -r requirements.txt

4. Run the training script:
python mnist_classifier.py

## Notes
The training process will output loss values per epoch and a plot showing the loss curve
After training, the model is saved as mnist_model.pth
The expected test accuracy is 97%-98% after 5 epochs

## License
This project is licensed under the MIT License
Please see the LICENSE file for details

## Disclaimer
This project is intended for educational purposes
Please cite the MNIST dataset appropriately if using results from this project