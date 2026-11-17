# Crop Disease Classification (Uganda)

Convolutional neural networks built in PyTorch, using pre-trained models and training callbacks, to classify crop-disease images from Uganda into five categories.

## Problem
Crop disease threatens food security and farm income. Early, accurate identification from a simple photo helps farmers and extension workers act before a disease spreads.

## Process
1. **Data exploration:** inspected the images in each of the five classes and checked how balanced the classes were.
2. **Pre-processing:** resized and normalised the images and built training and validation data loaders.
3. **Transfer learning:** loaded a pre-trained convolutional network, froze its feature layers and replaced the final layer with a new five-class output layer.
4. **Training callbacks:** used early stopping, model checkpointing and learning-rate scheduling to train efficiently and keep the best model.
5. **Evaluation:** compared training and validation curves to check for over-fitting, and used a confusion matrix to review errors by class.
6. **Prediction:** produced class predictions for new, unseen leaf images.

## Tools
Python · PyTorch · torchvision · scikit-learn · pandas · Matplotlib · Jupyter

## Skills shown
Transfer learning · Fine-tuning · Training callbacks · Multi-class classification · Model evaluation

## Repository status
The project notebooks and scripts are being prepared for upload and will be added here shortly.

## Programme
Completed as part of the **WorldQuant University Applied AI Lab: Deep Learning for Computer Vision** (Jul 2025).

## Author
**Uchenna Francis Onyeka** · MSc FinTech with Business Analytics, University of Westminster
[LinkedIn](https://www.linkedin.com/in/uchenna-onyeka) · [GitHub](https://github.com/uchenna8243)
