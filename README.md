Digit Classifier from Scratch (NumPy Neural Network)

A simple deep learning project built from scratch using only NumPy to classify handwritten digits from the MNIST dataset.  
This project implements the core building blocks of a neural network forward pass, backpropagation, gradient descent, and parameter updates without completly relying on machine learning libraries like TensorFlow or PyTorch.  

Neural Network Architecture
- Input Layer: 784 neurons (28×28 image flattened)  
- Hidden Layer: 128 neurons, ReLU activation  
- Output Layer: 10 neurons, Softmax activation  
- Loss Function: Cross-Entropy  
- Optimizer: Stochastic Gradient Descent (SGD)  

How It Works
1. nitialize weights & biases → using Xavier initialization for stability.  
2. Forward pass → compute activations with ReLU + Softmax.  
3. Loss calculation → measure prediction error with cross-entropy.  
4. Backward pass (Backpropagation) → compute gradients.  
5. Update parameters → adjust weights and biases with gradient descent.  
6. Repeat over epochs → accuracy improves with training.  
