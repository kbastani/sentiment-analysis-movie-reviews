Movie Review Sentiment Analysis Benchmark
================================

An iPython notebook that tests [Graphify's](http://github.com/graphify/graphify) feature extraction and selection algorithm as a logistic regression classifier. This classifier is benchmarked against [Stanford's Large Movie Review Dataset](http://ai.stanford.edu/~amaas//data/sentiment/) and [Cornell Movie Review Dataset](http://www.cs.cornell.edu/people/pabo/movie-review-data/).

Content
-------

- The slides are at [https://github.com/kbastani/sentiment-analysis-movie-reviews/tree/master/pdf](https://github.com/kbastani/sentiment-analysis-movie-reviews/tree/master/pdf)

- The interactive notebooks are in the main folder.

Classification Accuracy
--------
- Scores `~90%` accuracy on Cornell Movie Review dataset.
  - http://nbviewer.ipython.org/github/kbastani/sentiment-analysis-movie-reviews/blob/master/Cornell%20Moview%20Review%20Dataset%20-%20Sentiment%20Analysis.ipynb
- Scores `~80%` accuracy on Stanford Large Movie Review dataset.
  - http://nbviewer.ipython.org/github/kbastani/sentiment-analysis-movie-reviews/blob/master/Stanford%20Large%20Movie%20Review%20Dataset%20-%20Sentiment%20Analysis.ipynb

###Feature learning
- Features are extracted and learned using Java and Neo4j, and evaluated by building a logistic regression classifier on a weighted tf-idf feature vector.

Viewing the notebooks online
----------------------------
The content of the notebooks can be viewed online through nbviewer.ipython.org.

Installing Python
-----------------
For a true interactive use of the notebooks you need to install Python, IPython (for notebooks) and the required libraries scikit-learn, matplotlib and numpy.

Windows
-------
You can install everything at once using a complete scientific Python distribution.
Two good ones are the [Enthought Python distribution](http://www.enthought.com/products/epd.php) (EPD, free for academic use) or  [Python-(x, y)](http://code.google.com/p/pythonxy/) (free for everyone).

Mac
---
For OS X, you can also use the [Enthought Python distribution](http://www.enthought.com/products/epd.php) or the [scipy-superpack](http://fonnesbeck.github.com/ScipySuperpack/).


Linux
-----
Just use your package manager, for example on ubuntu or debian, use
``apt-get install python ipython python-matplotlib python-numpy python-sklearn``.

Version requirements
--------------------
You need to make sure to have at least IPython >= 0.11 installed. You can update using the programm ``easy_install``.

Installing Scikit-learn
-----------------------
More tips on installing scikit-learn can be found on the [scikit-learn website](http://scikit-learn.sourceforge.net/dev/install.html#installing-an-official-release).


More Resources
--------------
This repository was modeled off of [tutorial_ml_gkbionics](https://github.com/temporaer/tutorial_ml_gkbionics).
