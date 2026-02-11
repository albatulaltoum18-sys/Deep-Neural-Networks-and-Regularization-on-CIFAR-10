Deep Neural Networks and Regularization on CIFAR-10

This project explores the impact of regularization techniques on deep neural networks using the CIFAR-10 dataset. The main objective is to analyze overfitting behavior and evaluate how different regularization methods improve model generalization.

Overview
A fully connected neural network (MLP) was implemented using TensorFlow and Keras. Two versions of the model were trained: a baseline model without regularization and a regularized model incorporating L2 regularization, dropout, early stopping, and data augmentation.

Methodology
The CIFAR-10 dataset was normalized and one-hot encoded before training. The baseline model consists of three dense layers with ReLU activation. The regularized model applies L2 weight decay, dropout layers, and early stopping to reduce overfitting. Data augmentation techniques such as horizontal flipping, rotation, and zoom were also applied.

Experiments and Analysis
Training and validation loss and accuracy curves were analyzed to evaluate convergence and stability. The baseline model showed clear signs of overfitting, while the regularized model demonstrated improved generalization and more stable learning behavior.

Results

Regularization significantly reduced overfitting

Validation accuracy improved compared to the baseline model

Training stability and convergence were enhanced

Early stopping prevented unnecessary over-training

Tools and Technologies
Python
TensorFlow
Keras
NumPy
Matplotlib
Jupyter Notebook

Project Files

DeepLearning_Regularization_CIFAR10.ipynb

DeepLearning_Regularization_Report.pdf

How to Run
Open the Jupyter Notebook file and execute the cells sequentially after installing the required libraries.

Purpose
This project explores regularization techniques and their effect on deep neural network performance.

Author
Albatul Altoum