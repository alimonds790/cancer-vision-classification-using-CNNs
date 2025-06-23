# cancer-vision-classification-using-CNNs

# Problem Description

In this project, we are tasked with building a deep learning model to classify microscopy images of cells as either infected or uninfected. The dataset consists of thousands of 96x96 color images, each labeled as 0 (uninfected) or 1 (infected). The images are provided in separate training and test folders, with corresponding labels for the training set.

The main challenges include handling a large dataset, preventing overfitting, and achieving high classification accuracy. Data augmentation and regularization techniques are essential to improve the model's generalization.

# Goal

The goal is to develop a robust convolutional neural network (CNN) using TensorFlow/Keras that can accurately predict the infection status of unseen cell images. The model should be trained, validated, and evaluated using appropriate metrics such as accuracy, precision, recall, and F1 score. Finally, the trained model will be used to generate predictions for the test set, and the results will be exported in a format suitable for submission.
