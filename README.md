# prodigy_02

Cat vs Dog Image Classifier

This project implements a deep learning model that classifies images as either a cat or a dog using TensorFlow and Keras. The model is built using a Convolutional Neural Network (CNN) and trained on datasets downloaded from Kaggle.

The notebook automatically downloads the cat and dog image datasets, organizes them into folders, and trains the model using ImageDataGenerator for preprocessing and validation splitting.

Model Architecture:
- Convolutional layers with ReLU activation
- MaxPooling layers for downsampling
- Flatten layer
- Dense fully connected layer
- Sigmoid output layer for binary classification

Training Details:
- Image size: 150 x 150
- Batch size: 32
- Validation split: 20%
- Loss function: binary crossentropy
- Optimizer: Adam

After training, the program allows users to input the path of an image and predicts whether the image contains a cat or a dog.

Technologies used:
Python, TensorFlow, Keras, NumPy, Matplotlib, KaggleHub, Jupyter Notebook.

This project demonstrates the basic workflow of building, training, and using a CNN for image classification.
