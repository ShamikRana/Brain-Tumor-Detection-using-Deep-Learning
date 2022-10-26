# Brain Tumor Detection using Deep Learning
- This project focuses on detection of various types of brain tumors with the help of Head CT Scan images
- This is a multi-class image classification problem
- The model was built with Convolutional Neural Network on Tensorflow

# Methods Used
- Data Visualisation
- Data Preprocessing
- Deep Learning (CNN)

# Technologies Used
- Python
- Jupyter
- Numpy, Pandas, Matplotlib, OpenCV
- Scikit Learn, Tensorflow, Keras

# Project Description
- Project began with fetching of data from [Kaggle Dataset](https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri)
- Images are converted into array using numpy and OpenCV
- Dataset is divided in 90:10 ratio as test and train dataset
- Deep Leaning algorithm of Convolutional Neural Network is applied for classification of images

# Convolutional Neural Network Characteristics
- Image Input Shape - (150,150,3), kernel size - (5,5), activation - relu
- Pooling Operation - (2X2) Max Pooling
- Dropout Layers - 0.2
- Optimizer - 'SGD', loss - 'categorical_crossentropy', metrics - ['accuracy'], epoch - 50
- Accuracy - 0.9990, Loss - 0.0050 (approx. 7sec/epoch on NVIDIA Tesla P100 GPU)

# Findings
The architecture and parameter used in this neural network are capable of producing accuracy of 90.21% on Test Data which is pretty good. It is possible to achieve more accuracy on this image dataset using data augmentation and fine tuning of network parameters for training.

# How to Use
- Fork this repository to have your own copy
- Clone your copy on your local system
- Install necessary packages
