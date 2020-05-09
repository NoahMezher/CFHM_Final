# Survival Analysis for Deep Learning

This is an implementation based on the [tutorial on survival analysis](https://k-d-w.org/blog/2019/07/survival-analysis-for-deep-learning/), also referred to as time-to-event analysis or reliability analysis. This notebook trains a convolutional neural network to predict time to a (generated) event from MNIST images, using a loss function specific to survival analysis.

Note: This code was not able to run on my Windows machine due to problems with pip and installing packages. I ran it on Google Collaborate with great success, and downloaded the .ipynb file to run.

The only steps I really changed was how pip was installing scikit-survival. There were many issues with the dependencies for it such as osqp and cvxopt. Details describing how to install the correct modules are outlined in the first cell of the notebook.

I have also included the wheel files for you to try yourself, although it must be in a virtual environment.

Screenshots for my output including setup data, prediction data, tensorboard output, and resultant data can be found in the screenshots/ folder of this repository.

## Getting started

The easiest way to run this notebook is [Google Colaboratory](https://colab.research.google.com/github/sebp/survival-cnn-estimator/blob/master/tutorial.ipynb). If you want to run this notebook locally, you have to make sure the following dependencies are installed:

- [numpy](https://www.numpy.org/)
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-survival](https://github.com/sebp/scikit-survival/)
- [tensorflow](https://www.tensorflow.org/)
