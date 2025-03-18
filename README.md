# MNIST Classification Project

This repository contains multiple models for the MNIST dataset, including two different architectures for handwritten digit classification.

## Models & Results

- **Fashion Model:** Achieved 90% accuracy.
- **Simple Model:** Achieved 97% accuracy.  
  The simple model was also compared with ResNet to gain better insights into overfitting and model generalization.

## Running the Models

If you don't have a GPU available, you can still run the experiments using [Google Colab](https://colab.research.google.com/). This platform provides free GPU resources that can significantly speed up training.

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/devcristi/mnist.git
   ```
2. Change to the repository directory:
   ```bash
   cd mnist
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the desired model script:
   ```bash
   python simple_model.py
   ```
   or
   ```bash
   python fashion_model.py
   ```

## Requirements

Refer to the [requirements.txt](requirements.txt) file for a list of dependencies.

## Additional Information

This project was designed to provide insights into model performance on MNIST, focusing on comparing a simple architecture with a more complex ResNet model, particularly with regards to understanding overfitting.
