# Bird Detection with Automatic Recording Unit (ARU)
This repository contains code for developing an Automatic Recording Unit (ARU) using a Raspberry Pi to detect bird vocalizations. The ARU collects audio data from Intaka Island in Cape Town, manually annotates the data, and trains a model to classify future spectrograms based on the presence of bird sounds.

Table of Contents
Introduction
Installation
Usage
Data
Preprocessing
Model Training
Predictions
Results
Contributing
License
Introduction
Bird vocalizations are an important indicator of biodiversity and ecosystem health. The goal of this project is to develop an ARU that can automatically detect bird sounds in audio recordings. The ARU is built using a Raspberry Pi and trained using machine learning techniques.

# Installation
In Progress .....
You can check the main.ipynb file for now!

# Preprocessing
The data is preprocessed before training the models. The preprocessing steps include low-pass filtering, downsampling, and converting the audio into spectrograms. The spectrograms are then used as input for the models.

# Model Training
Two models are trained in this project. Model 1 is a simple convolutional neural network (CNN) architecture, while Model 2 is a modified version of the VGG architecture. Both models are trained using the preprocessed data and evaluated using accuracy metrics.

# Predictions
The trained models can be used to make predictions on new audio files. The models take spectrograms as input and output a binary prediction indicating the presence or absence of bird sounds. The predictions can be further analyzed and processed as needed.

# Results
The performance of the trained models is evaluated using test audio files. The models are able to accurately classify the presence or absence of bird sounds in the test data. Model 2 performs better than Model 1, showing higher accuracy and better discrimination between bird sounds and background noise.
