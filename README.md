# Singular Value Decomposition vs. Support Vector Machines: A Comparative Study for Handwritten Digit Recognition Using the MNIST Dataset

This exciting project involves the development and implementation of a unique algorithm for handwritten digit recognition using Singular Value Decomposition (SVD) and the MNIST dataset. The MNIST dataset, a large database of handwritten digits, will serve as both training and testing data for the algorithm, with the ultimate goal of creating a robust and accurate recognition system.

The project will commence with the preprocessing of the MNIST images to ensure they are suitable for analysis. Following this, SVD, a powerful matrix factorization technique, will be applied to extract key features from the images. These features will then be used to train a classifier, which will be capable of recognizing handwritten digits in new, unseen images from the MNIST dataset.

In the second phase of the project, the accuracy of the SVD-based algorithm will be evaluated and compared with that of a model using Support Vector Machines (SVM), a well-established machine learning method for image classification. Both models will be tested on the same subset of the MNIST dataset, and their performances will be compared based on metrics such as accuracy, precision, recall, and F1 score.

This project offers a practical application of advanced mathematical techniques and a valuable comparison between two different approaches to image classification. The insights gained from this project could contribute to the ongoing development of more effective and efficient handwritten digit recognition systems.

In essence, this project is a comprehensive exploration of the application of SVD and SVM in handwritten digit recognition using the MNIST dataset. It provides a unique opportunity to understand the relative strengths and weaknesses of these two approaches, potentially paving the way for future advancements in the field of image recognition.

**Files**: 
- Dataset - [MNIST Dataset](https://www.kaggle.com/datasets/hojjatk/mnist-dataset)
- samples_hand - Own dataset with images

**Author:** [Vladislav Polyakov](https://github.com/VladekQ)

**Notebook:** [svd_mnist_classifier.ipynb](https://github.com/VladekQ/svm_svd_mnist_classifier/blob/main/svd_mnist_classifier.ipynb)

## Results & Conclusion
<p align="center">
  <img src="https://github.com/VladekQ/svm_svd_mnist_classifier/assets/72941961/bfcaaaf5-f436-430e-833a-34d24c37083c" width="700" />
  <img src="https://github.com/VladekQ/svm_svd_mnist_classifier/assets/72941961/f5cf97aa-29e9-4b95-b304-bc2a84256d88" width="700" />
</p>

In conclusion, the project **"Singular Value Decomposition vs. Support Vector Machines: A Comparative Study for Handwritten Digit Recognition Using the MNIST Dataset"** provided a comprehensive analysis of the performance of two popular machine learning techniques in the context of handwritten digit recognition. The Singular Value Decomposition (SVD) method demonstrated superior performance over the Support Vector Machines (SVM) method, achieving higher scores in all evaluated metrics. Specifically, SVD achieved an accuracy, precision, recall, and F1 score of 0.96, outperforming SVM which scored 0.91 in all these metrics. 

Moreover, SVD showed a significant advantage in terms of training and prediction time, taking only about 27 seconds to train and predict compared to SVM's 131 seconds. 

This study therefore suggests that SVD is a more effective and efficient choice for handwritten digit recognition tasks, offering a more reliable and accurate classification of numbers in images while requiring less training time. However, it is important to consider other factors such as scalability and generalizability to other datasets when selecting a machine learning method for a specific application.

## Implementation on own pictures
<p align="center">
  <img src="https://github.com/VladekQ/svm_svd_mnist_classifier/assets/72941961/6456a512-5836-485d-b8e9-5a0be9d1fe0a" width="700" />
</p>

Accuracy Score on own dataset by LinearSVC: **66.7%**

Accuracy Score on own dataset by SVD: **94.4%**

**Even on your own dataset (which may not be ideal), the singular value decomposition method shows the best result**
