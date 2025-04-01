# Hand-Written-Digit-Classification

## Introduction

This project focuses on classifying handwritten digits using deep learning techniques. Convolutional Neural Networks (CNN) and Residual Neural Networks (ResNet) are used along with image augmentation to enhance model performance.

## Dataset

Link: https://www.kaggle.com/datasets/hojjatk/mnist-dataset

The dataset consists of grayscale images of handwritten digits, each measuring 28x28 pixels with a single intensity channel. These images serve as the input for both model architectures.

## Data Preprocessing & Augmentation

To improve generalization and robustness, various image augmentation techniques are applied, including:

- Rotation
- Translation




## Model Architectures

### Convolutional Neural Network (CNN)

This network consists of several convolutional layers followed by ReLU activation functions. The layers are as follows:

1. **Conv2D Layer**: Input channels=1, Output channels=4, Kernel size=3, Stride=2, Padding=1
2. **ReLU Activation**
3. **Conv2D Layer**: Input channels=4, Output channels=8, Kernel size=3, Stride=2, Padding=1
4. **ReLU Activation**
5. **Conv2D Layer**: Input channels=8, Output channels=16, Kernel size=3, Stride=2, Padding=1
6. **ReLU Activation**
7. **Conv2D Layer**: Input channels=16, Output channels=16, Kernel size=3, Stride=2, Padding=1
8. **ReLU Activation**
9. **Conv2D Layer**: Input channels=16, Output channels=10, Kernel size=3, Stride=2, Padding=1
10. **Flatten Layer**

This architecture is designed for efficient feature extraction with decreasing spatial dimensions.


### Residual Neural Network (ResNet)

![image](https://github.com/user-attachments/assets/78de7905-8167-4f4a-a766-e173f915dc42)





