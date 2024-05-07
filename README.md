# Prediction of covid-19 on the basis of chest X-ray
This Python script is designed for building and training a Convolutional Neural Network (CNN) model to classify chest X-ray images into two categories:
COVID-19 positive and normal. Here's a brief description:

Data Preparation:
The script loads chest X-ray images from two directories: COVID-19 positive and normal.
It resizes the images to 40x40 pixels and normalizes the pixel values to the range [0, 1].
Model Creation:
The script constructs a CNN model using the Keras Sequential API.
The model consists of convolutional layers with max pooling followed by fully connected layers.
The output layer has a sigmoid activation function for binary classification.
Model Training:
The script compiles the model using binary cross-entropy loss and the Adam optimizer.
It trains the model on the training data and validates it on the test data for 10 epochs.
Evaluation and Visualization:
After training, the script plots the training and validation accuracy and loss curves.
It evaluates the model performance using metrics such as confusion matrix, classification report, and accuracy score.
Model Accuracy : 92%
Output:
The script provides model evaluation results and displays the predicted labels for the test data.
It outputs the confusion matrix, classification report, and accuracy score to assess the model's performance.
This script can serve as a starting point for building a CNN-based classifier for chest X-ray images in medical image analysis tasks related to COVID-19 detection. 
You can customize and extend the script based on your specific requirements and dataset characteristics.

