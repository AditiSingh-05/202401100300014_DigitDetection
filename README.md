# MNIST Data Loading and Preprocessing

This project demonstrates how to load and preprocess the MNIST dataset using TensorFlow and Keras.

## Prerequisites
Ensure you have the following dependencies installed:
- Python
- TensorFlow
- Keras

You can install TensorFlow using:
```sh
pip install tensorflow
```

## Code Overview
This script loads the MNIST dataset, which consists of handwritten digit images and their corresponding labels.

### Libraries Used
- `tensorflow` and `keras`: For deep learning operations
- `Sequential`, `Dense`, `Flatten`: Keras layers for building models

### Code Snippet
```python
import tensorflow
from tensorflow import keras
from tensorflow.keras import Sequential
from tensorflow.keras.layers import Dense, Flatten

(X_train, y_train), (X_test, y_test) = keras.datasets.mnist.load_data()

X_test.shape

y_train
``` 
```
(10000, 28, 28)  # Shape of X_test

array([5, 0, 4, ..., 5, 6, 8], dtype=uint8)  # Sample output of y_train
```





