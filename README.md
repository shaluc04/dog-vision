## End-to-End Multi-Class Dog Breed Classification 🐶
This notebook builds an end-to-end multi-class classifier using TensorFlow 2.0 and TensorFlow hub.

#### Problem
Identifying the breed of a dog given the image of a dog.

#### Data
The data we're using is from Kaggle's dog breed identification competition : https://www.kaggle.com/c/dog-breed-identification/data

Some information about the data:

- We're dealing with images (unstructured data) (so it's probably best we use deep learning/transfer learning).
- There are 120 breeds of dogs (this means there are 120 different classes - multi-class).
- There are around 10,000+ images in the training set (these images have labels).
- There are around 10,000+ images in the test set (these images don't have labels).
