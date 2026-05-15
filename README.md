# Siamese Facial Identification

A machine learning project implementing Siamese Neural Networks for facial identification and verification.

## Overview

This project uses Siamese neural networks to learn similarity metrics between facial images. The model is trained to distinguish between pairs of faces - determining whether two faces belong to the same person or different people.

## Features

- Siamese network architecture for facial verification
- Face similarity metric learning
- Binary classification: same person vs different people
- Jupyter notebook-based implementation

## Requirements

- Python 3.x
- TensorFlow/Keras
- NumPy
- OpenCV
- Matplotlib (for visualization)

## Project Structure

This repository contains Jupyter notebooks implementing the Siamese facial identification system.

## Usage

1. Open the Jupyter notebooks in this repository
2. Install required dependencies
3. Follow the notebook cells to train and evaluate the model

## How It Works

The Siamese network architecture consists of:
- Two identical neural networks (weight sharing)
- Shared feature extraction layers
- A distance metric layer to compare embeddings
- Binary output indicating whether input faces match

## Results

The model learns to extract facial features and compute similarity scores between face pairs, achieving high accuracy in distinguishing between same and different individuals.

## Author

Youssef M. Allam
