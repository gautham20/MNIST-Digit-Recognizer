# MNIST-Digit-Recognizer
Neural network implementation of Digit Recognizer using MNIST database

Neural Network in built using [numpy](http://www.numpy.org/) for learning purpose (more abstract python packages were not used) 

###Architectures

A1 - 784 input nodes - 40 hidden nodes - 10 output nodes

A2 - 784 input nodes - 100 hidden nodes - 10 output nodes

###Terminology

simple - Quadratic cost function, random weights initialization
CC - Crossentrophy cost function
R - L2 Regularization
WI - Normalized Weights intialization

Hyper-parameters Learning rate (eta) and Regularization factor (lambda) was varied for each run

##Accuracy Achieved

| Neural Network Setup      | training accuracy           | Validation set Accuracy  |
| ------------------------- |:---------------------------:| ------------------------:|
| A1 simple                 | 96.192                      | 94.72                    |
| A1 simple+CC              | 98.5                        | 95.92                    |
| A1 simple+CC+R            | 97.632                      | 96.84                    |
| A1 simple+CC+R+WI         | 97.71                       | 96.88                    |
| A2 simple+CC+R+WI         | 99.026                      | 97.88                    |

The accuracy achieved in test data is __97.73__
