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

<img src="/images/Linear_regression_gif.gif" alt="Linear_Regression" width="852" height="569">

### Chapter 2: [K-Nearest Neighbors (KNN)](KNN.ipynb)
A simple supervised classifier predicated on the assumption that data is most likely to be correctly classified in the same manner as the majority of instances nearby. 

<img src="/images/KNN_output.png" alt="KNN" width="852" height="569">

### Chapter 3: [K-Means Clustering](k_means.ipynb)
An unsupervised clustering method which segments a dataset into a designed number *k* clusters. Euclidean distance is the primary underlying metric. 

<img src="/images/Clustering_gif.gif" alt="K Means Clustering" width="638" height="469">

### Chapter 4: [Simple Perceptron](Simple_perceptron.ipynb)
A simple binary classifier capable of learning linearly separable patterns.

<img src="images/Simple_Perceptron_gif.gif" alt="Simple Perceptron" width="1122" height="834">

### Chapter 5: Feedforward Artificial Neural Network
A network of neurons whose connections can be represented with an acyclic graph. 

## Further reading 
1. [Pattern Recognition and Machine Learning by Christopher M. Bishop](https://www.springer.com/gp/book/9780387310732)
2. [Machine Learning: A Probabilistic Perspective by Kevin P. Murphy](https://mitpress.mit.edu/books/machine-learning-1)
3. [Deep Learning by Ian Goodfellow, Yoshua Bengio, and Aaron Courville](https://www.deeplearningbook.org/)
4. [Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow by Aurélien Géron](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
5. [The Elements of Statistical Learning by Trevor Hastie, Robert Tibshirani, and Jerome Friedman](https://web.stanford.edu/~hastie/ElemStatLearn/)
6. [Python Machine Learning by Sebastian Raschka and Vahid Mirjalili](https://www.packtpub.com/product/python-machine-learning-third-edition/9781789955750)
7. [Introduction to Machine Learning with Python by Andreas C. Müller and Sarah Guido](https://www.oreilly.com/library/view/introduction-to-machine/9781449369880/)
8. [Machine Learning Yearning by Andrew Ng](http://www.mlyearning.org/)
9. [Data Science for Business by Foster Provost and Tom Fawcett](https://www.oreilly.com/library/view/data-science-for/9781449374273/)
10. [Artificial Intelligence: A Modern Approach by Stuart Russell and Peter Norvig](http://aima.cs.berkeley.edu/)