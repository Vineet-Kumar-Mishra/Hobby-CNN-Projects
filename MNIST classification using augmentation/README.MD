# This is CNN model to classify 10 class MNIST problem
### The model presented is a basic model with 3 convolution layer having 32, 64 and 128 outputs/filters respectively. Each Conv2D layer has reLu as activation and we have used stride of 2 as a replacement for Maxpooling layer
### The feedforward layer is simple with 128 neurons with reLu activation accompanied by a dropout of 0.2. The final Dense layer i.e the output layer is having 10 neurons with softmax activation
### the Loss and accuracy have been plotted using history.
### The dataset can be easily obtained from keras.datasets.mnist in form of tuple of train set and test set.
### This is an updated model with augmentation using keras ImageDataGenerator
### The training accuracy is 99.02% and the test accuracy is 98.94 % 
### The above accuracy proves that this model does not overfit as while training,val_accuracy > train_accuracy
### Note : The model has been trained with the use of GPU

