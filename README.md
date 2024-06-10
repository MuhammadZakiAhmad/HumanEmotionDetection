# Human Emotion Detection using CNN and Transfer Learning
Overview

This project involves training an image classifier from scratch on the Kaggle FER-2013 Dataset to detect emotions from facial expressions. The data consists of 48x48 pixel grayscale images of faces, categorized into one of seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.
Features

    Emotion Detection
    Data Cleaning
    Data Analysis
    Data Visualization
    Custom CNN Model Training
    Image Augmentation
    Transfer Learning with VGGNET
    Model Evaluation
    Confusion Matrix Plotting

Technologies

    Python
    Jupyter Notebook
    TensorFlow/Keras
    NumPy
    Pandas
    Matplotlib
    Seaborn

Project Description

The project is an Emotion Detection system built using computer vision and deep learning techniques. The main goal is to develop an intelligent system that can detect emotions from facial expressions in real-time.

Here's how the project works:
Data Preparation

    Dataset: The project uses the FER-2013 dataset available on Kaggle. It contains 48x48 pixel grayscale images of faces, categorized into one of seven emotions.
    Data Cleaning: Preprocessing and cleaning the dataset to ensure quality input data.
    Data Analysis: Analyzing the dataset to understand its structure and distribution.

Data Visualization

    Visualization: Visualize sample images from each emotion category.
    Random Image Plotting: Plotting random images from the dataset directory.
    Shape and Channel Checking: Ensuring images are correctly formatted.

Model Training

    Custom CNN Model: Built from scratch for emotion detection.
    Image Augmentation: Applying image augmentation techniques to improve model robustness.
    Transfer Learning with VGGNET: Using VGGNET for transfer learning to enhance performance.
    Image Generators: Initializing image generators for training and validation.
    Callbacks: Understanding and implementing callbacks during training.
    Training: Training the models and plotting performance metrics.

Model Evaluation

    Evaluation: Evaluating the trained models using performance metrics.
    Confusion Matrix: Plotting the confusion matrix to visualize model performance.
    Predictions: Making predictions using the trained models.
