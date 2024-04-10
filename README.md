# Real-Time-Traffic-Sign-Recognition-using-CNN
German Traffic Sign Recognition with Low-Cost FPGA CNN Accelerator
This project aims to implement a low-cost Convolutional Neural Network (CNN) accelerator on FPGA for real-time German traffic sign recognition. The model is trained using the German Traffic Sign Recognition Benchmark (GTSRB) dataset, which consists of 43 different classes of traffic signs.

Getting Started
These instructions will help you set up the environment to run the code on your local machine or in a cloud-based environment like Google Colab.

Prerequisites
Make sure you have the following prerequisites installed:

Python 3.x
TensorFlow
NumPy
Pandas
OpenCV
Matplotlib


Model Architecture
The CNN model architecture used in this project is as follows:

Convolutional Layer 1: 6 filters with a kernel size of 3x3 and ReLU activation.
Depthwise Separable Convolution Layer 2: 2 filters with a kernel size of 3x3.
Convolutional Layer 3: 2 filters with a kernel size of 3x3 and ReLU activation.
Depthwise Separable Convolution Layer 4: 2 filters with a kernel size of 3x3.
MaxPooling Layers (x2).
Flatten Layer.
Dense Output Layer with softmax activation.
Results
After training the model for 3 epochs, the test data accuracy achieved is approximately 82.44%.

Acknowledgments
The project is inspired by the research and datasets available on Kaggle. Special thanks to Meow Meow for providing the GTSRB dataset.
