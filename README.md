# Neural Networks with Keras (MNIST Dataset)

This project demonstrates the implementation of **simple** and **complex neural networks** on the **MNIST handwritten digits dataset** using TensorFlow/Keras.

---

## Features
1. **Simple Neural Network**
   - One hidden layer with 5 neurons.
   - Achieves ~87% test accuracy.
   - Demonstrates the basics of feedforward neural networks.

2. **Complex Neural Network**
   - Custom multi-branch architecture using Keras Functional API.
   - Larger hidden layers (128, 160, 64 neurons).
   - Over 236K parameters for richer feature extraction.

---

## Tech Stack Used

This project uses the following technologies and libraries:

- **Python 3.x**  
  The core programming language used for implementing and experimenting with neural networks.

- **TensorFlow / Keras**  
  - **TensorFlow** is the open-source deep learning framework that powers the model training and evaluation.  
  - **Keras (high-level API)** is used for building models quickly with layers like `Dense`, `Flatten`, and advanced Functional API for complex architectures.  
  - Handles dataset loading (`mnist`), preprocessing, training loops, and model saving.

- **Matplotlib**  
  - A plotting library used to visualize MNIST images (handwritten digits).  
  - Helps in data exploration by showing how labels correspond to digit images.

- **NumPy (implicit via TensorFlow)**  
  - Provides efficient array and matrix operations.  
  - TensorFlow internally uses NumPy for numerical computations and dataset manipulation.

---

## Results
- **Simple Model**: ~87% test accuracy, Loss ~0.43  
- **Complex Model**: ~97.2% test accuracy, Loss ~0.0968  

The complex model clearly outperforms the simple baseline because:
- It has **more neurons and layers** (over 236K parameters vs ~4K).  
- It captures **richer feature representations** from handwritten digits.  
- However, it also requires **more computational resources** and has a higher risk of overfitting if not regularized properly.

---
