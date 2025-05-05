# 🧠 Handwritten Digit Recognition Model (MNIST)

This project contains a Convolutional Neural Network (CNN) built using TensorFlow/Keras to recognize handwritten digits from the MNIST dataset.

---

## 📌 Overview

The model is trained on the [MNIST dataset](http://yann.lecun.com/exdb/mnist/), which consists of 70,000 grayscale images (60,000 for training and 10,000 for testing) of handwritten digits (0–9), each sized 28×28 pixels.

---

## 📦 Requirements

- Python 3.7+
- pip
### Python Libraries

Install required packages:

```bash
pip install tensorflow numpy matplotlib
```
---

# Model Architecture
    - Input layer: 28×28 grayscale image
    - Conv2D (32 filters, 3x3 kernel, ReLU)
    - MaxPooling2D
    - Conv2D (64 filters, 3x3 kernel, ReLU)
    - MaxPooling2D
    - Flatten
    - Dense (128 units, ReLU)
    - Output Dense (10 units, softmax)


# 📈 Accuracy
    Training Accuracy ~ 99.54 %
    Validation Accuracy ~ 98.43 %
---
## Output

The model will be in the form of .h5 refers to Hierarchical Data Format 5 