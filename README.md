# Christopher_Cat
### Introduction
Christopher_Cat is one of the project; `Christopher` for familiarising with machine learning and other basic Artificial Intelligence concepts.

This repository highly depends on the tutorial provided by Tensorflow.

It is capable of the followings;
* Classify image between `cat` and `dog`
* Training the model continuously by loading previous model weights.
* Evaluate and predict any type of image that user wants to predict.

This repository is purely for educational purpose.

### Future Implementation
Data statistics visualization using `Tensorboard`

### Model Structure
Model is based on deep neural network with 2 hidden layers with Conv2D Rectified Linear Unit (ReLU),
with additional dropouts of 0.2 and maxpooling layers. Structure is referenced from official Tensorflow tutorial.

![Model Structure Graph](/docs/img/model_graph.png?raw=true)

### Results
Current Training results show that it has an accuracy of 0.74 with value accuracy of 0.768

![Accuracy and Loss graph](/docs/img/accuracy_loss_screenshot.png?raw=true)

### Libraries Used
1. Tensorflow: 2.0
1. Pillow: 6.2.1
1. Scipy: 1.4.0
1. Numpy: 1.17.4

### Reference
[Tensorflow Tutorial: Image Classification](https://www.tensorflow.org/tutorials/images/classification)

[image_classification_part1.ipynb](https://colab.research.google.com/github/google/eng-edu/blob/master/ml/pc/exercises/image_classification_part1.ipynb#scrollTo=DgmSjUST4qoS)
