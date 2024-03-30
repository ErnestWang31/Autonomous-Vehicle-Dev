# Autonomous-Car-ML


This repository contains code and resources for a self-driving car behavioral cloning project. The project focuses on training a neural network to drive a car autonomously in a simulated environment. The neural network learns to mimic human driving behavior by training on a dataset of images and corresponding steering angles.

Data
The project uses a dataset of images taken from a car's perspective, along with corresponding steering angle labels. The data is stored in the 'Track' directory, including the 'driving_log.csv' file, which contains the image file paths and steering angles.

Model
The neural network model used for behavioral cloning is based on the NVIDIA architecture. It consists of convolutional layers followed by fully connected layers to predict the steering angle.

Training
The model is trained using a generator function that augments the training data with techniques like random zoom, pan, brightness adjustment, and flipping. Training parameters and results can be found in the Jupyter Notebook.

Results
The trained model can drive the car autonomously in a simulated environment. The project includes a visualization of the training and validation loss over epochs.

