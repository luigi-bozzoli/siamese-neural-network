# Siamese neural network

Neural network which, given two images, verifies the existence of kinship and recognizes the type of the latter.

## Languages and Tools
+ Python
+ [OpenCV](https://opencv.org/)
+ [Keras](https://keras.io/)
+ [Google Colaboratory](https://colab.research.google.com/notebooks/intro.ipynb?utm_source=scs-index)
+ [TensorFlow](https://www.tensorflow.org/)

## Description
The aim of the project is to build a model, using **transfer learning**, able to discriminate between related and unrelated people and to recognize the type of relationships existing between them:
**mother-son**, **mother-daughter**, **father-son**, **father daughter**.

### Dataset used
[KinFaceW](https://www.kinfacew.com/datasets.html)\
[Families in the Wild](https://www.kaggle.com/c/recognizing-faces-in-the-wild/data)

### Base model
The [base model](https://github.com/CVxTz/kinship_prediction/blob/master/README.md) used for the transfer learning is a **siamese neural network**.\
It uses the same weights while working in tandem on two different input vectors to compute output vectors.


## Contributors
[Antonio Martucci](https://github.com/AntonioMartucci)\
Domenico Napolitano

## License
[MIT](https://choosealicense.com/licenses/mit/)
