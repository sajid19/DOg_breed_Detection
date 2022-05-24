This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.x and TensorFlow Hub.
Identifying the breed of a dog given an image of a dog.
The data we're using is from Kaggle's dog breed identification competition.
Some information about the data:

* We're dealing with images (unstructured data) so it's probably best we use deep learning/transfer learning.
* There are 120 breeds of dogs (this means there are 120 different classes).
* There are around 10,000+ images in the training set (these images have labels).
* There are around 10,000+ images in the test set (these images have no labels, because we'll want to predict them).
