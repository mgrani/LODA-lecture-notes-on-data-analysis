LODA-Lecture Notes on Data Analysis
===================================

Lecture notes (in form of slides) and excercises in Python using ipython-notebook for teaching data and media analysis.
It includes introductions to Python, Numpy, Scipy, Scikit-Learn, SimpleCV.
It covers the topics Supervised/Unsupervised Learning, Signal Analysis, Image Analysis, Text and Web-Media Analysis. 

Presentation
============
The lecture notes are optimized for presentation. In order to use them, invoke

  ipython nbconvert --to=slides --post serve path-to-lecture-notes

to start the presentation (a browser window should open automatically).

Acknowledgment
==============

This work is largely based on a number of great tutorials and resources all over the web, compiled by great people from very different domains. Without their effort and their will to make their hard work open access, i would have not been able to compile this tutorial. The individual contributions are listed in the beginning of every part.  


Outline
=======

0. Introduction - Why, What, Who, How
   1. The point of view of [Web Mining (Course Web Mining
      Project@University Passau)](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/0.INTRO/Course-Web%20Mining%20Project%20(5944P).ipynb)

1. Part I: Scientific Programming in Python

   1. [Introduction](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-1-Introduction.ipynb)
   2. [Programming Basics](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-2-Python-Programing-Basics.ipynb)
       1. [Exercise 2.1.: Python Standard Data Structures](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/exercises/Exercise%20DSiP-2-1-Python%20Standard%20Data%20Structures.ipynb)
   3. [Numpy in a Nutshell](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-3-Numpy.ipynb)      
	  1. [Exercise 3.1. Data Structures and Operations in Numpy] (http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/exercises/Exercise%20DSiP-3-1-Numpy.ipynb)
   4. Scipy in a Nutshell
   5. [Mathplotlib in a Nutshell](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-5-Matplotlib.ipynb)
	   1. [Exercise DSiP-5-1-Analysing the Iris Dataset with Mathplotlib] (http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/exercises/Exercise%20DSiP-5-1-Analysing%20the%20Iris%20Dataset%20with%20Mathplotlib-.ipynb)
   6. [Pandas based Data Analysis](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/DSiP-6-Pandas.ipynb)
       1. [Exercise 6.1. Analysing New York Open Data with Pandas] (http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/I-Data-Science-in-Python/exercises/Exercise%20DSiP-6-1-Pandas-NYC-Open-Data.ipynb)
2. Part II: Machine Learning and Data Mining \[in Python\]
   1. Machine Learning in a Nutshell with scikit-learn

        1. [Overview and Preprocessing](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-in-a-Nutshell-with-scikitlearn-overview-and-preprocessing.ipynb)
        2.[Supervised Learning: Classification and Regression](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-in-a-Nutshell-with-scikitlearn-Supervised-Learning.ipynb)
        3.[Unsupervised Learning: Clustering](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-in-a-Nutshell-with-scikitlearn-clustering.ipynb)
        4.[Unsupervised Learning: Projections and Manifolds](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-in-a-Nutshell-with-scikitlearn-projections-and-manifold-learning.ipynb)

   2. Machine Learning Basics

      1. On the Data
      2. Regression
        - [A simple Example](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/2.ML-DM-Simple-Regression.ipynb)
        - [Least Mean Square Algorithm - a Gradient Descent approach to regression](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Example-LMS.ipynb)
        - [Regression and Classification - using the analytical solution](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Example-Regression.ipynb)
      3. Concept Learning
      4. Measuring Performance

   3. Decision Trees
      1.  Decision Tree Basics
      2.  Impurity Functions
      3.  Decision Tree Algorithms
      	  1. [ID 3 in Python](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Example-DecisionTree.ipynb)
      4.  Decision Tree Pruning
      

   4. Statistical Learning

      1.   Probability Basics
      2.  Bayes Classification
      3. Graphical Models

   5. Linear Models
   6. Kernel Models
   7. Neuronal Networks

      1.   Perceptron Learning
      2.  Multilayer Perceptrons
      3. Deep Learning

   8. Ensemble Classifiers
   9. Cluster Analysis
      1. [Clustering with scikit-learn](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Clustering-with-scikit-learn.ipynb)
   10. Dimensiontality Reduction and Manifold Learning
      1. [Dimensionality Reduction and Manifold Learning with scikit-learn](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/II.ML-and-DM/II.ML-and-DM-Projection-and-Manifold-Learning-with-scikit-learn.ipynb)
   11. Association Rules
   12. Reinforcement Learning
   13. Deep Learning

2. Part III: Natural Language Processing \[in Python\]
   1. [An Introduction to NLTK](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/III.NLP/III.NLP-with-NLTK-Short-Intro.ipynb)
       1. [NLTK Exercise](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/III.NLP/exercise/III.NLTK-Intro-Exercise.ipynb)


5. Part V. Web Mining Applications
    1. [Crawling and Analysing Twitter](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/V.Web-Mining-Applications/V.WMA-Crawling-Twitter.ipynb)
	     1. [Exercise: Crawling and Analysing Twitter](http://nbviewer.ipython.org/urls/raw.github.com/mgrani/LODA-lecture-notes-on-data-analysis/master/V.Web-Mining-Applications/exercises/Exercises%20Crawling%20Twitter%20with%20Python.ipynb)

Helpful Links
-

* [Python 101 Cheatsheet](http://nbviewer.ipython.org/urls/bitbucket.org/hrojas/learn-pandas/raw/master/lessons/Python_101.ipynb) 
    

License
=======

This work is licesend under a Creative-Commons 3.0 license. 

