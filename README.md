# Neural Network from Scratch with NumPy

A minimal two‑layer neural network implementation in pure NumPy—no TensorFlow or PyTorch—trained on the MNIST digit‑recognizer dataset.
This repository demonstrates how to build, train, and evaluate a simple two‑layer feedforward neural network from scratch using only NumPy. You will see how to:
- Load and preprocess the MNIST “Digit Recognizer” dataset.
- Initialize weights and biases with Xavier (Glorot) initialization.
- Implement forward propagation (ReLU activation in the hidden layer, softmax output).
- Compute cross‑entropy loss.
- Implement backward propagation and update parameters via gradient descent.
- Track training cost and validation accuracy over epochs.
- Generate predictions on the test set for Kaggle submission.

No high‑level ML frameworks (TensorFlow, Keras, PyTorch) are used—only NumPy for numerical operations.
