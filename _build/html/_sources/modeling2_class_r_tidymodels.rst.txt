***********************************************************
Modeling 2: Intro to classifiers with R using tidymodels
***********************************************************

**NOTE: This is new material for Winter 2025**


In class we'll spend some time learning about using logistic regression for binary classification problems - i.e. when our response variable has two possible outcomes (e.g. customer defaults on loan or does not default on loan). We'll explore other simple classification approaches such as k-Nearest Neighbors and basic classification trees. Trees, forests, and their many variants have proved to be some of the most robust and effective techniques for classification problems.


This module will take us 1.5 weeks.

   
Readings
---------

* ISLR - Sec 3.5 (kNN), Sec 4.1-4.3 (Classification, logistic regression), Ch 8 (trees)
* `ISLR Tidymodels labs <https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/08-tree-based-methods.html>`_ - Sec 4.1, 4.2 (Classification and logistic regression) and Ch 8 (Tree based methods)
* The `Tidy Modeling with R <https://www.tmwr.org/>`_ book also has useful info throughout.


Downloads and other resources
------------------------------

* `Downloads_StatModel2_tidymodels.zip <https://drive.google.com/file/d/135fn2CNFfRWj2miUxZhMLp8v7xTBpccF/view?usp=sharing>`_

Activities 
-------------

We will work through a number of Quarto documents as we 
learn to build basic classifiers using R. Everything is available
in the Downloads file above.

Intro to classification problems and the k-Nearest Neighbor technique
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

In this first part we'll:

* get a sense of what classification problems are all about,
* get our first look at the very famous Iris dataset,
* use a simple, model free technique, known as k-Nearest Neighbors, to try to classify Iris species using a few physical characteristics.

You'll use **knn.qmd** and follow along with this screencast:

* `SCREENCAST - Intro to classification with kNN <https://youtu.be/zxoce5Lu2ro>`_ (26:18)

Logistic regression
^^^^^^^^^^^^^^^^^^^

Logistic regression is a variant of multiple linear regression in which the response variable is binary (two possible outcomes). It
is a commonly used technique for binary classification problems. It's definitely more "mathy" than
kNN. I'll try to help you develop some intuition and understanding of this technique without
getting too deeply into the math/stat itself. See the Explore section at the bottom of this page
for some good resources on the underlying math and stat of logistic regression.

You'll use **logistic_regression.qmd** and these screencasts:

We'll start with a short introduction to the problem, the data and 
an ill-advised multiple linear regression model. We will also
partition the data into training and test sets.

* `SCREENCAST - Intro to the problem <https://youtu.be/ukDnTLbK45Q>`_ (6:44)

Next, we will review the main ideas of the logistic regression model.
We'll create a null model and then use ``glm()`` to build our first 
few models. We'll see some of the challenges in interpretation of
statistical models (and this is a tiny model).

* `SCREENCAST - Logistic regression models <https://youtu.be/XE4_meeIzC8>`_ (6:42)
* `SCREENCAST - Fitting with glm() <https://youtu.be/SdkRjLHjv5U>`_ (12:40)

We'll learn how to use tidymodels to build, fit and assess logistic
regression models.

* `SCREENCAST - Logistic regression with tidymodels <https://youtu.be/4nHTQKfxDog>`_ (19:06)
* `SCREENCAST - Impact of thresholds and ROC curves <https://youtu.be/tR8uGs1g1_8>`_ (7:45)


Decision trees
^^^^^^^^^^^^^^^

Now on to learning about decision trees and variants such as random forests. 
You'll use **trees.qmd** with these screencasts.

We'll start with a short introduction to the problem and the data. Data
partioning and a bit of data exploration are done. Then we'll build a simple decision tree. So, how do decision trees decide how to create their branches? We'll take a very
brief look at this and point you to some resources to go deeper if you want.

* `SCREENCAST - Intro to decision trees <https://youtu.be/1dYakSwg_lo>`_ (21:41)

Now we'll look at some more advanced tree based models.

* `SCREENCAST - Bagging, random forests and beyond <https://youtu.be/rN59cd1YkHs>`_ (16:49)


Putting it all together - the Kaggle Titanic challenge (OPTIONAL) 
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This is the famous Kaggle practice competition that so many people used
as a first introduction to predictive modeling and to Kaggle. A number of very nice
tutorials have been developed to help newcomers to Kaggle. So, take 
a look at the following R Markdown document. In addition to a little 
bit of EDA and some basic model building, you'll find some interesting
attempts at feature engineering as well as creating output files suitable
for submitting to Kaggle to get scored. The Titanic Challenge is
perpetually running, so feel free to try it out. You can't pay much
attention to the leader board as people have figured out ways to
get 100% predictive accuracy.

* **titanic/Titanic_kaggle.Rmd**



Explore (OPTIONAL)
-------------------

* StatQuest YouTube Channel - Josh Starmer
    - `StatQuest: Confusion matrix <https://www.youtube.com/watch?v=Kdsp6soqA7o>`_
    - `StatQuest: Sensitivity and specificity <https://www.youtube.com/watch?v=vP06aMoz4v8>`_
    - `StatQuest: Maximum likelihood <https://www.youtube.com/watch?v=XepXtl9YKwc>`_
    - `StatQuest: Odds and Log(odds) <https://www.youtube.com/watch?v=ARfXDSkQf1Y>`_
    - `StatQuest: Logistic regression <https://www.youtube.com/watch?v=yIYKR4sgzI8>`_ - there are a bunch of follow on videos with various details of logistic regression
    - `StatQuest: Random Forests: Part 1 - Building, using and evaluation <https://www.youtube.com/watch?v=J4Wdy0Wc_xQ>`_
* `About unbalanced classes and oversampling methods <https://stats.stackexchange.com/questions/357466/are-unbalanced-datasets-problematic-and-how-does-oversampling-purport-to-he>`_
* `The vtreat package for data preparation for statistical learning models <https://winvector.github.io/vtreat/>`_
* `Predictive analytics at Target: the ethics of data analytics <https://www.nytimes.com/2012/02/19/magazine/shopping-habits.html>`_
* `Kappa statistic defined in plain english <https://stats.stackexchange.com/questions/82162/cohens-kappa-in-plain-english>`_ - Kappa is a stat used (among other things) to see how well a classifier does as compared to a random choice model but which takes into account the underlying prevalence of the classes in the data.
* `Frustration: One Year with R <https://github.com/ReeceGoding/Frustration-One-Year-With-R>`_



