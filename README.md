# ML-knn-rnn
Implementing and Evaluating KNN and RNN Classifiers: A Study on Handwritten Digits and Breast Cancer Classification

This project focuses on implementing and evaluating K-Nearest Neighbors (KNN) and Radius Nearest Neighbors (RNN) classifiers using both manual implementation and `scikit-learn`.

The first part applies KNN to the MNIST dataset of handwritten digits, with data preprocessing and normalization. Two distance metrics—Euclidean and Manhattan—are used, and k-fold cross-validation determines the optimal \( k \). Evaluation metrics include confusion matrices, accuracy, and macro-average F1 scores.

The second part explores RNN on the Breast Cancer dataset to classify tumors as malignant or benign. RNN uses a radius-based approach to identify neighbors, with cross-validation conducted for varying radius values to optimize performance. Predictions on the test data highlight RNN's limitations for high-dimensional datasets like MNIST, emphasizing challenges such as the curse of dimensionality.
