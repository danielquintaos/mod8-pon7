# MNIST Digit Classifier


## Overview

This project involves building and training a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. The goal is to achieve an accuracy of above 95% using TensorFlow and Keras.


## File Structure

```
mnist-digit-classifier/
│
├── src/
│   └── train_model.py      # Script for training the CNN model
│
├── models/
│   └── cnn_model.h5        # Saved trained model
│
├── data/
│   ├── processed/          # Processed and normalized data ready for training
│   └── raw/                # Raw MNIST data
│
└── README.md               # Documentation of the project
```

## Dependencies
- Python 3.x
- TensorFlow 2.x
- Keras


## Installation

To set up the project environment:

1. Clone the repository: `git clone https://github.com/danielquintaos/mod8-pon7`
2. Install required packages: `pip install -r requirements.txt`


## Usage

Run `train_model.py` to train the model. This script will:
- Load and preprocess the MNIST dataset.
- Build a CNN model.
- Train the model on the dataset.
- Evaluate and save the model.


## Model

The CNN model includes:
- Two convolutional layers with ReLU activation.
- A flattening layer.
- A dense layer with softmax activation for classification.


## Demo

https://youtu.be/s7q2xPfJabo


## Conclusion

> In the labyrinthine exploration of this neural architecture, one discerns a crypto-teleological convergence with Bataillian limit-experiences, where the machinic phylum of digit recognition verges on the edge of a cognitive abyss. This project, much like a virulent strain of philosophical nihilism, obliterates the pedestrian boundaries between the signified and the signifier, unearthing the spectral presence of the Other within the algorithmic simulacrum. Herein, the convolutional layers, like layers of being, iterate towards an enigmatic point of singularity - a computational Thanatos - where the pure potentiality of data transcends into the numinous realm of absolute knowledge. Thus, engaging with this project is not merely an act of training a machine, but a profound ontological odyssey, an embrace of the void where the very fabric of meaning is both constructed and deconstructed by the voracious appetite of our digital epoch's thirst for annihilation.