# This is CNN model to classify 10 class fashion MNIST problem
### The model presented is a basic model with 3 convolution layer having 32, 64 and 128 outputs/filters respectively. Each Conv2D layer has reLu as activation and we have used stride of 2 as a replacement for Maxpooling layer
### The feedforward layer is simple with 128 neurons with reLu activation accompanied by a dropout of 0.2. The final Dense layer i.e the output layer is having 10 neurons with softmax activation
### the Loss and accuracy have been plotted using history.
### The dataset can be easily obtained from keras.datasets.fashion_mnist in form of tuple of train set and test set.
### This is a basic model without using any data augmentation
### The training accuracy is 94.52% and the test accuracy is 89.78 % 
### Note : The model has been trained without the use of GPU
