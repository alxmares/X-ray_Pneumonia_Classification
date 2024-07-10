# X-ray Pneumonia Classification using TPUs

This project involves the classification of pneumonia from chest X-ray images using Tensor Processing Units (TPUs). The dataset used is from a study published in [*Cell*](https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5).

## Project Overview

The goal of this project is to leverage TPUs to build and train a deep learning model that can classify chest X-rays as either normal or pneumonia.

![Sample Images](assets/samples.jpg)

## Key Features
- **Data Loading and Preprocessing**: The dataset is loaded from Google Cloud Storage, and images are preprocessed.
- **Model Training on TPU**: Utilizes TensorFlow's TPU strategy for efficient training.
- **Data Imbalance Handling**: Implements techniques to address the imbalance in the dataset.
- **Model Evaluation**: Evaluates the trained model and visualizes the results.

## Model Evaluation

![Evaluation Results](assets/graphs.jpg)

## Conclusion

This project demonstrates the effective use of TPUs for training a deep learning model to classify pneumonia from chest X-ray images. Advanced techniques and handling data imbalances result in high accuracy and robustness.

Contributions are welcome! Submit issues or pull requests to enhance the project.

