# Dog Breeds Classifier

## Table Of Contents

- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Requirements](#requirements)
- [Neccessary Files](#neccessary-files)
- [How to Run](#how-to-run)

## Introduction

This repository contains all my work for the Udacity's Machine Learning Nanodegree Program.

The goal in this project was to build a Convolutional Neural Network (CNN) for identifying dog breeds.
To accomplish this, I applied data augmentation techniques (random scaling, cropping, and flipping) to help the network
generalize leading to better performance. Then, defined a benchmark CNN from scratch using several convolutional and
max pooling layers. Finally, I used transfer learning to train and test different architectures (VGG-16, ResNet-50),
and picked the best model based on F1-score metric.

## Project Overview

There are many different dog breeds around the world, and some of them with similar physical characteristics. Being
able to recognize each dog breed is a challenging task even for humans, therefore the necessity of using machine
learning for performing this task. A convolutional neural network (CNN) will be used to accomplish this challenge.
The aim of this project is to build a pipeline to process real-world, user-supplied images. Given an image of a dog,
the algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify
the resembling dog breed. If neither a dog nor a human is detected, then an error message is output.

## Requirements

This project uses the following software and Python libraries:

- [Python](https://www.python.org/downloads/release/python-364/)
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [scikit-learn (v0.17)](https://scikit-learn.org/0.17/install.html)
- [Matplotlib](https://matplotlib.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html).

If you do not have Python installed yet, it is highly recommended that you install the
[Anaconda](https://www.anaconda.com/distribution/) distribution of Python, which already has the above packages and
more included.

## Neccessary Files

This repository contains three files needed to solve the project.

1. **dog_app.ipynb:** This is the main file where I performed the work on the project.
2. **dog_app.html:** This is an HTML report of the Jupyter notebook.
3. **haarcascades directory:** OpenCV's implementation of Haar feature-based cascade classifiers to detect human faces
in images.

## How to Run

In the Terminal or Command Prompt, navigate to the folder on your machine where you've put the project files, and then
use the command:

```bash
jupyter notebook dog_app.ipynb
```

 to open up a browser window or tab to work with your notebook.
 Alternatively, you can use the command:

 ```bash
jupyter notebook
```

or

```bash
ipython notebook
```

and navigate to the notebook file (dog_app.ipynb) in the browser window that opens.
