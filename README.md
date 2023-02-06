# garbage-detection
An object recognition script to identify various types of recyclable materials.

This script uses deep learning to recognize different types of recyclable materials. The model is built using the Keras framework and the MobileNetV2 architecture.

## Requirements
- pandas
- numpy
- os
- keras
- matplotlib
- tensorflow
- sklearn

## Model
The model is composed of multiple dense and dropout layers, as well as a GlobalAveragePooling2D layer. The model is optimized using the Adam optimizer.

## Image Preprocessing
An ImageDataGenerator is used for image preprocessing.

## Evaluation
The performance of the model is evaluated using a classification report from scikit-learn's metrics module.

## Usage
Need to train and generate the model then save as binary. Load the model and test using a dataset.

Google Colab was used to train this model.