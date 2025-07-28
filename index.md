# Data Science Portfolio
---
## Machine learning

### LSTM Neural Network for Time Series Prediction

The following article sections will briefly touch on LSTM neuron cells, give a toy example of predicting a sine wave then walk through the application to a stochastic time series. The article assumes a basic working knowledge of simple deep neural networks.

---
### Text Classification

It is slightly simplified implementation of Kim's Convolutional Neural Networks for Sentence Classification paper in Tensorflow.

---
### Gesture Recognizer

Gesture recognition via CNN neural network implemented in Keras + Theano + OpenCV

Key Requirements: Python 3.6.1 OpenCV 3.4.1 Keras 2.0.2 Tensorflow 1.2.1 Theano 0.9.0 (obsolete and not supported any further)

Suggestion: Better to download Anaconda as it will take care of most of the other packages and easier to setup a virtual workspace to work with multiple versions of key packages like python, opencv etc.

---
### Human Activity Recognition

Human Activity Recognition (HAR) using smartphones dataset and an LSTM RNN. Classifying the type of movement amongst six categories:

WALKING,
WALKING_UPSTAIRS,
WALKING_DOWNSTAIRS,
SITTING,
STANDING,
LAYING.
Compared to a classical approach, using a Recurrent Neural Networks (RNN) with Long Short-Term Memory cells (LSTMs) require no or almost no feature engineering. Data can be fed directly into the neural network who acts like a black box, modeling the problem correctly. Other research on the activity recognition dataset can use a big amount of feature engineering, which is rather a signal processing approach combined with classical data science techniques. The approach here is rather very simple in terms of how much was the data preprocessed.

Let's use Google's neat Deep Learning library, TensorFlow, demonstrating the usage of an LSTM, a type of Artificial Neural Network that can process sequential data / time series.
