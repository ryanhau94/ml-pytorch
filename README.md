# ml-pytorch
Homework for [*Introduction to Machine Learning* by Duke University](https://www.coursera.org/learn/machine-learning-duke) as well as some other learning materials for deep learning.

- To install PyTorch via Anaconda:
```shell
conda install pytorch torchvision -c pytorch
```

- To install PyTorch via pip (Python 3):
```shell
pip3 install torch torchvision
```

A good online notebook service is [Colab](https://colab.research.google.com/notebooks/intro.ipynb) by Google, where you can also play with TensorFlow. The best part is that you also have free access to GPU resources.

A GPU computing support is desirable here as the training may take much longer if you play with CPUs. 
## Learning path:
1. [Logistic_Regression.ipynb](Logistic_Regression.ipynb): MNIST datasets and basic PyTorch operations to build a logistic regression model. Accuracy: 0.903
    - See [Broadcasting.ipynb](others/Broadcasting.ipynb) and [Vectorization.ipynb](others/Vectorization.ipynb) to learn some tricks with vectors in Python.
2. [Logistic_Regression_OOD.ipynb](Logistic_Regression_OOD.ipynb): Building a logistic regression model with PyTorch in an object-oriented design (OOD) manner. Accuracy: 0.903
3. [MultiLayer-Perceptron.ipynb](MultiLayer-Perceptron.ipynb): One hidden layer with 500 nodes. Accuracy: 0.925
4. [Image-RGB_channels.ipynb](Image-RGB_channels.ipynb): Simple examples of input and output of images.
5. [Convolutional_Neural_Networks.ipynb](Convolutional_Neural_Networks.ipynb): A simple CNN model with 2 convolutional layers and 2 fully-connected layers optimized by Adam. Accuracy: 0.987
    - See [CNN_Early-Stop.ipynb](CNN_Early-Stop.ipynb) for a simple, yet not strict, demonstration for early stop.