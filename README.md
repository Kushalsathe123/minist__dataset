# minist__dataset
To train and test model on minist dataset 
Here is the link to download dataset
https://pjreddie.com/media/files/mnist_train.csv


Here is the preview of the UI


![ezgif-3-1ee69f3235](https://github.com/Kushalsathe123/minist__dataset/assets/92160019/6f83b761-146e-4db5-a61e-8cbdca93b17b)






# MNIST Digit Recognition

This project implements a digit recognition system using the MNIST dataset and a convolutional neural network (CNN) model. It includes scripts for training the model, testing its performance, and integrating it into a GUI application where users can draw digits for classification.

## Description

The project consists of the following components:

1. **Data Loading and Preprocessing**: The MNIST dataset is loaded from a CSV file, and the images are reshaped and split into training and testing sets.

2. **Model Definition**: A CNN model is defined using Keras, comprising convolutional layers, max-pooling layers, and fully connected layers.

3. **Training**: The CNN model is trained on the training data to learn to recognize digits.

4. **Testing**: The trained model is evaluated on the testing data to assess its accuracy.

5. **Digit Prediction on Sample Image**: An example script demonstrates how to load a sample image, preprocess it, and use the trained model to predict the digit in the image.

6. **GUI Application**: A simple GUI application is created using Tkinter, allowing users to draw digits on a canvas, classify them using the trained model, and see the predicted digit displayed.

## Installation

1. Clone the repository:

gh repo clone Kushalsathe123/minist__dataset


2. Install the required Python dependencies:

pip install -r requirements.txt


## GUI Usage
Follow the on-screen instructions in the GUI application to draw digits and see them classified.

## Dependencies

- Python 3.x
- NumPy
- pandas
- Matplotlib
- scikit-learn
- Keras
- TensorFlow
- Tkinter
- OpenCV



## Acknowledgments

- The MNIST dataset is provided by Yann LeCun and can be found [here](https://pjreddie.com/media/files/mnist_train.csv).
- The GUI application design is inspired by various examples and tutorials available online.

