# This is CNN model to classify 10 class fashion MNIST problem
### The model presented is a basic model with 3 convolution layer having 32, 64 and 128 outputs/filters respectively. Each Conv2D layer has reLu as activation and we have used stride of 2 as a replacement for Maxpooling layer
### The feedforward layer is simple with 128 neurons with reLu activation accompanied by a dropout of 0.2. The final Dense layer i.e the output layer is having 10 neurons with softmax activation
### the Loss and accuracy have been plotted using history.
### The dataset can be easily obtained from keras.datasets.fashion_mnist in form of tuple of train set and test set.
### This is an updated model with augmentation using keras ImageDataGenerator
### The training accuracy is 85.43% and the test accuracy is 87.92 % 
### The above accuracy proves that this model does not overfit and val_accuracy > train_accuracy
