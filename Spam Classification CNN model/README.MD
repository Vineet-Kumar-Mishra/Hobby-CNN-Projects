# This is a spam classification model implemented using CNN
### 1. The sequences are 1 dimensional so we can use Conv1D to find the patterns
### 2. We have converted equal length sequences using tokenization followed by padding.
### 3. The Embedding layer creates vector of dimension = 25 (hyperparameter)
### 4. We have to the apply Conv1D layer followed by MaxPooling 1D layer.
### 5. We have used 3 Conv1D layer followed by MaxPooling1D layer with 32, 64, 128 filters each.
### 6. The Dense layer contains 1 neuron with softmax activation.
### 7. The Model achieves 99.56 % train accuracy and 98.27 % validation accuracy.
