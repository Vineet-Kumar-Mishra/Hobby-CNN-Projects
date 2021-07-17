
# This is CNN model to classify a person wearing mask or not.
### The model presented is a basic model with 3 convolution layer having 32, 64 and 128 outputs/filters respectively. Each Conv2D layer has reLu as activation accompanied by a Maxpooling layer of (2,2) and BatchNormalization layers.
### The feedforward layer is simple with 150 neurons with reLu activation accompanied by a dropout of 0.2. The final Dense layer i.e the output layer is having 2 neurons with softmax activation
### the Loss and accuracy have been plotted using history.
### The dataset can be easily obtained from kaggle.
### This model has augmentation done using keras ImageDataGenerator for regularization
### The training accuracy is 95.29% (due to augmentation) and the test accuracy is 98.08 %
### To make sure the accuracy is min 98 % we have used callbacks and created a class of callbacks to monitor the validation accuracy.
### The above accuracy proves that this model does not overfit and val_accuracy > train_accuracy
### The model has been trained for 100 epochs but due to callback the training stpos at 91st epoch.
