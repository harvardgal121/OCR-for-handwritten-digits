# OCR-for-handwritten-digits
This project aims to build an OCR for hand-written digits using an Artificial Neural Network.

DESIGN OF THE ANN

The ANN created to emulate an OCR for handwritten digits consists of:
1. An Input layer that has 784 inputs (Each image is flattened to 28 * 28 to input it)
2. Two hidden layers with 512 and 256 neurons respectively which use the "Relu" activation function.
3. The output layer has 10 neurons and uses "Softmax" Activation function
4. The loss model use is Cross Entropy function

During the creation of the ANN, the following factors have been played around with until maximum accuracy was obtained:
1. Number Of Hidden Layers
2. Number Of Neurons in each Hidden Layer
3. The Activation Function associated with each Hidden Layer
4. The Optimizer used to compile the ANN
5. Number of Epochs, and Batch Size.

RESULTS

Stochastic Descent Gradient

nb_epoch = 20

batch_size = 128

Accuracy = 95.75%


Adagrad

nb_epoch = 20

batch_size = 128

Accuracy = 98.32%


Adam

nb_epoch = 20

batch_size = 128

Accuracy = 98.11%
