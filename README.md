# prodigy_02

Cat vs Dog Image Classifier (SVM)

This project implements a machine learning model that classifies images as either a cat or a dog using a Support Vector Machine (SVM). The model is trained on image datasets downloaded from Kaggle.

The notebook automatically downloads the cat and dog image datasets, organizes them into folders, and preprocesses the images for training. Images are resized and converted into feature vectors before being used to train the SVM classifier.

Model Approach:
- Image preprocessing and resizing
- Conversion of images into numerical feature vectors
- Training a Support Vector Machine (SVM) classifier
- Binary classification for distinguishing cats and dogs

Training Details:
- Image size: 150 x 150
- Images flattened into feature vectors
- Dataset split into training and validation sets
- Classification using SVM

After training, the program allows users to input the path of an image and predicts whether the image contains a cat or a dog.

Technologies used:
Python, Scikit-learn, NumPy, Matplotlib, KaggleHub, Jupyter Notebook.

This project demonstrates the workflow of preprocessing image data and applying a Support Vector Machine (SVM) for image classification.
