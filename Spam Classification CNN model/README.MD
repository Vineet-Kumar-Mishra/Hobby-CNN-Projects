# This is a spam classification model implemented using CNN
### 1. The spam data is downloaded from kaggle and also available in repo. This file has encoding 'ISO-8859-1'
### 2. The sequences are 1 dimensional so we can use Conv1D to find the patterns
### 3. We have converted equal length sequences using tokenization followed by padding.
### 4. The Embedding layer creates vector of dimension = 25 (hyperparameter)
### 5. We have to the apply Conv1D layer followed by MaxPooling 1D layer.
### 6. We have used 3 Conv1D layer followed by MaxPooling1D layer with 32, 64, 128 filters each.
### 7. The Dense layer contains 1 neuron with softmax activation.
### 8. The Model achieves 99.56 % train accuracy and 98.27 % validation accuracy.
