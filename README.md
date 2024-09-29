# Multiclass Classification Problem on CIFAR-10 Dataset

This project tackles a multiclass classification problem using the **[CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)** dataset, a widely recognized benchmark for evaluating both Machine Learning and Deep Learning models. The primary objective is to compare the effectiveness, performance, and training time of three models in classifying images into their respective categories.

### Models Explored

The study explores three classification models, each offering a unique approach to the problem:

- **Ridge Regression for Classification**: Known for its simplicity and interpretability.
- **Random Forest**: A powerful ensemble-based model leveraging the strengths of multiple decision trees.
- **Deep Convolutional Neural Network (CNN)**: A sophisticated model with advanced pattern recognition capabilities.

### CNN Architecture

The **CNN architecture** used in this project was discovered using **[NAS-Bench-101](https://github.com/google-research/nasbench)**, a dataset created by Google Research for Neural Architecture Search (NAS). This structured search space ensures that the CNN architecture is optimized for efficient performance on image classification tasks like those found in the CIFAR-10 dataset.

### PCA-Transformed Evaluation

In addition to analyzing model performance and training time on the original dataset, this project evaluates **Ridge Regression** and **Random Forest** on a **Principal Component Analysis (PCA)**-transformed version of the CIFAR-10 dataset. This comparison helps determine whether dimensionality reduction can improve model accuracy or reduce training time.

### Conclusion

This study offers a comprehensive comparison between traditional machine learning models and modern deep learning techniques when applied to image classification. It evaluates the trade-offs between:

- Simplicity vs. complexity
- Training time vs. accuracy
- Raw data vs. dimensionality reduction (PCA)

By integrating NAS-Bench-101 for CNN architecture optimization, this project emphasizes the evolving role of neural architecture search in pushing the boundaries of deep learning performance.

