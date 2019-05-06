# Heart Disease Analysis

A simple repository showing the use of a neural network for a classification task.

The dataset being analysed is located at http://archive.ics.uci.edu/ml/datasets/Heart+Disease.

The framework being used for the machine learning is Keras.

The model has the following structure:
```
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
dense_4 (Dense)              (None, 30)                420       
_________________________________________________________________
dense_5 (Dense)              (None, 20)                620       
_________________________________________________________________
dense_6 (Dense)              (None, 1)                 21        
=================================================================
Total params: 1,061
Trainable params: 1,061
Non-trainable params: 0
```
