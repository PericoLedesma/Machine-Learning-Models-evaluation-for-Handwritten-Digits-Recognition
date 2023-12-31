# Machine Learning: Models evaluation for Handwritten Digits Recognition
## Description

This project aims at comparing handwritten digit recognition classifiers using various machine learning algorithms, such as Principal Component Analysis (PCA), Support Vector Machine (SVM), Decision Trees (DT) and K-Nearest Neighbor (KNN). The benchmark task is to classify the widely used MNIST dataset which consists of images of handwritten digits. A Convolutional Neural Network (CNN) model was trained on the MNIST dataset too and used as the gold- standard. The hypothesis was then proposed that despite seeing slight improvements after fitting the algorithms to the PCA data, these would still fail to perform better than a gold-standard algorithm like the CNN. It was found that the KNN and SVM models performed better than the DT model overall. And that there was a slight improvement after processing the data using a PCA. But in the end, all the algorithms underperformed when compared to the CNN, thus the hypothesis held.

## Learning outcomes

1) understand and appreciate universal challenges that arise in (almost) every machine learning (ML) project: curse of dimensionality, bias-variance tradeoff, choice of loss function, architecture design (structural bias), and know about standard coping strategies (dimension Reduction, regularization, cross-validation) 
2) give a coarse overview of the rich landscape of modern ML (supervised / unsupervised / reinforcement learning, 
different modeling attitudes, goals and methods in different subfields of ML) 
3) understand basic algorithmic techniques that is sufficient to allow him/her to practically apply these techniques by programming from scratch or using a high-level toolbox 
4) easily and quickly implement simple (but not necessarily poorly performing) linear, baseline ML pipelines for supervised learning problems 
5) design, implement, run, test and evaluate a more complex, multi-module, nonlinear ML pipeline for supervised learning problems, possibly including unsupervised components
