---
layout: default
title: X-ray Pneumonia Classification
---



## Tools and Technologies Used

![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white) 
![Keras](https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white) 
![TPU](https://img.shields.io/badge/TPU-%23F7DF1E.svg?style=for-the-badge&logo=google-cloud&logoColor=white) 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 
![Jupyter](https://img.shields.io/badge/Jupyter-%23F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)


## Key Results


![Accuracy](https://img.shields.io/badge/Accuracy-95%25-brightgreen?style=for-the-badge) 

![Precision](https://img.shields.io/badge/Precision-93%25-blue?style=for-the-badge) 

![Recall](https://img.shields.io/badge/Recall-96%25-blue?style=for-the-badge) 

![F1-Score](https://img.shields.io/badge/F1--Score-94%25-blue?style=for-the-badge) 


These results indicate a high performance of the model in distinguishing between normal and pneumonia-affected X-ray images.

![Evaluation Results](assets/graphs.jpg)

## Model Architecture

- **Base Model**: Utilized a pre-trained InceptionV3 model on ImageNet, which was fine-tuned on the X-ray dataset to improve its sensitivity and specificity for pneumonia classification.
- **Layers Added**: Custom dense layers added to adapt the model to the binary classification task.
- **Optimizer**: Adam optimizer with a learning rate scheduler to ensure efficient training.
- **Loss Function**: Binary cross-entropy to handle the two-class problem.


## Dataset

- **Source**: The dataset used in this project is from the [Chest X-Ray Images (Pneumonia)](https://www.cell.com/cell/fulltext/S0092-8674(18)30154-5), which is a publicly available dataset consisting of 5,863 X-ray images.
- **Classes**: The dataset contains two classes: "NORMAL" and "PNEUMONIA".
- **Preprocessing**: Images were resized to 180x180 pixels, and data augmentation was applied to improve model generalization.

![Sample Images](assets/samples.jpg)

* * *

## 🚀 **Explore More Projects!**

### [📚 Check out all my projects on GitHub Pages](https://alxmares.github.io)

* * *
