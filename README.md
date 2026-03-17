Sports Person Image Classifier

This project is a machine learning-based image classification system that identifies famous sports personalities from images. The system uses computer vision techniques and machine learning algorithms to analyze facial features and classify the image into one of several predefined sports personalities.

The model extracts features from images using wavelet transformation and image preprocessing techniques, and then applies a trained classification model to predict the most likely sports personality.

Features

Image preprocessing using OpenCV

Feature extraction using Wavelet Transform

Machine learning classification using Scikit-learn

Model deployment using Flask API

Ability to classify images of multiple sports personalities

Sports Personalities Included

Lionel Messi

Maria Sharapova

Roger Federer

Serena Williams

Virat Kohli

Technologies Used

Python

OpenCV

NumPy

PyWavelets

Scikit-learn

Flask

Project Workflow

Collect and organize image dataset for each sports personality.

Detect faces and eyes using Haar Cascade classifiers.

Apply wavelet transform to extract meaningful image features.

Train a machine learning model using the extracted features.

Save the trained model and class dictionary.

Deploy the model using a Flask server to classify new images.
