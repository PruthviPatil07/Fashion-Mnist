# Fashion MNIST Classification

## Overview
This repository contains a machine learning project that classifies images from the Fashion MNIST dataset using deep learning techniques. The dataset consists of grayscale images of 10 different clothing categories.

## Dataset
The Fashion MNIST dataset includes:
- 60,000 training images
- 10,000 test images
- 28x28 grayscale images
- 10 classes: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

## Project Structure
- `Fashion_Mnist.ipynb`: Jupyter Notebook containing data preprocessing, model training, and evaluation.
- `README.md`: Project documentation.

## Requirements
To run the notebook, install the following dependencies:
```bash
pip install numpy pandas matplotlib tensorflow keras
```

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Fashion-MNIST.git
   ```
2. Navigate to the project folder:
   ```bash
   cd Fashion-MNIST
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Fashion_Mnist.ipynb
   ```

## Model Overview
- Used a Convolutional Neural Network (CNN) for image classification.
- Applied techniques like dropout and batch normalization for better generalization.
- Achieved competitive accuracy on the test set.

## Results
- Training Accuracy: **97%**
- Test Accuracy: **97%**

## Future Improvements
- Implement data augmentation to enhance model robustness.
- Experiment with different architectures like ResNet or EfficientNet.

## Author
Pruthviraj Patil 

