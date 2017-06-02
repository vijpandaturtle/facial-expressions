# Facial Expression Classification

This project is an attempt to provide a solution for recognizing facial expressions using supervised learning. This project uses a convolutional neural network trained using a labelled dataset of images of different human faces.

## Dataset
This project uses the challenges in representation learning dataset from kaggle which can be downloaded from [here.](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge)

## How to get Started
For convenience purposes, I have put all of my code in a jupyter notebook. So, to get started you can clone the repo or download the zip file, and goto your command line or terminal
**For Windows**
```
>>> activate environment
>>> cd my-directory
>>> jupyter notebook
```
**For Ubuntu**
```
>>> source activate environment
>>> cd my-directory
>>> jupyter notebook
```
I have included instructions for two operating systems since I trained my model using both of them. You can find instructions for OSX(Mac) [here.](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/execute.html)

### Requirements
You require a python 3 environment (preferably a conda environment) with the following packages installed
* Tensorflow
* Numpy
* Matplotlib
* Pandas
* Scikit-learn
* Scipy
* Jupyter notebook

## Notes
This project uses a conv net that is custom made and trained on a gpu. The accuracy is 56 %. 
