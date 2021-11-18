## End-to-End Multi-Class Dog Breed Classification 🐶
This notebook builds an end-to-end multi-class classifier using TensorFlow 2.0 and TensorFlow hub.

### What is multi-class classification?
In machine learning, *multiclass or multinomial classification* is the problem of classifying instances into one of three or more classes. 
There are multiple categories but each instance is assigned **only one**, therefore such problems are known as multi-class classification problem.
Examples include:
- Face classification.
- Fruits and vegetables recognition.
- Optical character recognition.
- Hand written digit recognition.

#### Problem
> Identifying the breed of a dog given the image of a dog.

#### Data
The data we're using is from Kaggle's dog breed identification competition : https://www.kaggle.com/c/dog-breed-identification/data

Some information about the data:

- We're dealing with images (unstructured data) (so it's probably best we use deep learning/transfer learning).
- There are 120 breeds of dogs (this means there are 120 different classes - multi-class).
- There are around 10,000+ images in the **training set** (these images have labels).
- There are around 10,000+ images in the **test set** (these images don't have labels).

### Neural Networks with Tensorflow
Unstructured data can be text, images, videos, audios, basically the data which is not in a defined or structured format. There are no predefined rows, columns, values, or features in the Unstructured data, and is messier than structured data. Neural networks are designed in such a way that they mimic the human brain capacity and are therefore more robust in solving these types of problems. They are extremely useful in finding patterns that are too complex for being manually extracted and taught to recognize to the machine.

Helpful resource for Neural networks: https://towardsdatascience.com/understanding-neural-networks-what-how-and-why-18ec703ebd31

[TensorFlow](https://www.tensorflow.org/) is a free and open-source software library for machine learning and artificial intelligence. It can be used across a range of tasks but has a particular focus on training and inference of deep neural networks. I'll be using Tensorflow to build the multi-class classifier using neural networks.

Helpful resource for understanding basics of tensors: https://machinelearningmastery.com/introduction-to-tensors-for-machine-learning/


#### Steps followed:
* 




