# ASL Recognition with Deep Learning

## Overview
American Sign Language (ASL) is the primary language used by many deaf individuals in North America, and it is also used by hard-of-hearing and hearing individuals. The language is as rich as spoken languages and employs signs made with the hand, along with facial gestures and bodily postures.

In this project, I train a convolutional neural network to classify images of ASL letters. After loading, examining, and preprocessing the data, I train the network and test its performance.

## Data
The dataset comes from DataCamp, [here](https://app.datacamp.com/)

## Libraries Used
- numpy
- TensorFlow
- Matplotlib
- Keras
- scikit-learn (PCA, KMeans, StandardScaler)

## Cleaning and Preprocessing
- Since the data is already clean, luckily, we did not have to do data preprocessing

## Techniques
- One-hot encoding for 3 layers of letters
- Convolutional neural network in Keras
- Evaluate model's accuracy using a built-in function
