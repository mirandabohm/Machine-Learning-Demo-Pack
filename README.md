# Machine Learning Demo Pack : Jupyter Notebooks for Aspiring ML Engineers, Data Explorers, and Cognitive Scientists

This series of Jupyter Notebooks will demonstrate eight fundamental machine learning algorithms. Each notebook is interactive and downloadable, with cells that can be individually manipulated and run.

Some degree of experience with Python, including modules Numpy, Pandas, and Matplotlib, is expected; however, this is not prohibitively true. Any capable beginner to the language with a basic grasp of its intricacies should be able to follow the added commentary. 

## Getting Started with Jupyter Notebooks
I used Python v. 3.7.6 and Anaconda 4.8.3. 

## Dependencies

**NumPy** (for array manipulation): https://docs.scipy.org/doc/numpy/user/install.html
```
$conda install numpy
```
**Pandas** (for convenient data handling): 
```
$conda install numpy
```
**Matplotlib** (for visualizations): 
https://matplotlib.org/users/installing.html
```
$conda install matplotlib
```
Check whether modulle is installed on your system in the following way, replacing, if necessary, 'numpy' with the relevant name: 
```
$python
>>> import numpy 
>>> numpy.__version__
```
If you receive the following error, try re-installing:
```
ModuleNotFoundError: No module named 'numpy'
```

## Notebooks:

### Chapter 1: [Linear Regression](Linear_regression.ipynb)
A supervised technique iteratively estimating, and evaluating, a line of 'best fit.' Most useful for datasets with strongly implied linear trends satisfying all assumptions. 

![Linear_Regression](/images/Linear_regression_gif.gif)


### Chapter 2: K-Nearest Neighbors (KNN)
A simple supervised classifier. 

### Chapter 3: [K-Means Clustering](k_means.ipynb)
An unsupervised clustering method which segments a dataset into a designed number *k* clusters. Euclidean distance is the primary underlying metric. 

![K Means Clustering](/images/Clustering_gif.gif)

### Chapter 4: Naïve Bayes
A probabilistic classifier assuming feature independence. 

### Chapter 5: Decision Tree
A non-parametric, intuitive approach to regression and classification. 

### Chapter 6: Support Vector Machine
Script for a basic support vector machine. 

### Chapter 7: Simple Perceptron
A singular neuron capable of learning linearly separable patterns.   

### Chapter 8: Feedforward Artificial Neural Network
A network of neurons whose connections can be represented with an acyclic graph. 

## Resources for Additional Learning
{ Cited }