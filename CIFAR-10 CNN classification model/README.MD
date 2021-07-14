# This is CNN model to classify 10 class CIFAR-10 problem
### The model presented is a basic model with 3 convolution layer having 32, 64 and 128 outputs/filters respectively. Each Conv2D layer has reLu as activation accompanied by a Maxpooling layer of (2,2) and BatchNormalization layers.
### The feedforward layer is simple with 1024 neurons with reLu activation accompanied by a dropout of 0.2. The final Dense layer i.e the output layer is having 10 neurons with softmax activation
### the Loss and accuracy have been plotted using history.
### The dataset can be easily obtained from keras.datasets.cifar-10 in form of tuple of train set and test set.
### This model has augmentation done using keras ImageDataGenerator for regularization
### The training accuracy is 76.73% and the test accuracy is 80.72 % 
### The above accuracy proves that this model does not overfit and val_accuracy > train_accuracy
