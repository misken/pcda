***********************************************
Modeling 1: Overview and linear regression in R
***********************************************

Intro and Objectives
====================

One of the workhorses of statistical predictive modeling is the family of linear models. We'll do things like multiple linear regression for numeric predictions and logistic regression as a classifier for binary response variables. We'll use these relatively simple models as a way to also learn about important modeling topics such as partitioning data into training and test sets, model training, validation and diagnostics. We'll also use regression to introduce the notion of parameter estimation, error metrics for assessing model fit and for comparing candidate models against each other. These topics underlie all of statistical learning algorithms. 
   
Readings
========

* PDSwR - Ch 5, 7.1
* RforE - Ch 19 and 21
* ISLR - Ch 1-3 and 4.1-4.3

`An Introduction to Statistical Learning with applications in R <https://statlearning.com/>`_

This is an outstanding book, which is available as a free pdf. ISLR covers the main statistical learning topics at a nice introductory level. There is a more mathy version that preceded it called Elements of Statistical Learning. It also has a `freely available pdf <https://web.stanford.edu/~hastie/ElemStatLearn/>`_.

I will be listing the associated reading that you can do from ISLR as we explore various statistical learning topics - starting with linear regression.

* `In-depth introduction to machine learning in 15 hours of expert videos <https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/>`_ - The ISLR authors have created a whole series of video lectures based on their book.

Downloads and other resources
=============================

* `Downloads_StatModels1.zip <https://drive.google.com/file/d/1mJVvSPQo4bTvL0Rs-hyqRpTCaPaJoHxJ/view?usp=sharing>`_

If you are rusty on statistics, there's a really good OpenIntro Stats book available as a free online book or you can pay what you want for a paperback copy. It includes R based material.

* `OpenIntro Stats <https://www.openintro.org/book/ims/>`_

Activities
================================

We are going to work through a series of tutorials exploring the topic
of building, using and evaluating predictive linear regression models.

* `SCREENCAST - Overview of statistical modeling session <https://youtu.be/qdZR3ekeSW8>`_ (5:32)
* **0_ProbDists_notes.Rmd**
    - random variate generation
    - probability distribution computations
    - `SCREENCAST - Probability distributions in R <https://youtu.be/jXA0L_l2jMs>`_ (5:44)
* **1_LinRegModels_notes.Rmd**
    - basics of correlation
    - simple linear regression
    - `SCREENCAST - Simple linear regression <https://youtu.be/zxeLqMloAkc>`_ (20:45)
* **2_MultLinRegModels_notes.Rmd**
    - dealing with missing data
    - partition into training and test datasets
    - `SCREENCAST - MLR - Part 1: imputation of missing values <https://youtu.be/JT35e0dZ06k>`_ (5:39)
    - `SCREENCAST - MLR - Part 2: partition into train and test <https://youtu.be/XyHsw0Bru2c>`_ (2:47)
    - `SCREENCAST - MLR - Part 3: some EDA <https://youtu.be/viXD-Q_4VFs>`_ (4:10)
    - `SCREENCAST - MLR - Part 4: fitting simple additive models <https://youtu.be/tNRlzys0aa8>`_ (6:36)
    - `SCREENCAST - MLR - Part 5: fitting models with interaction terms <https://youtu.be/Az0npFu4Q_M>`_ (4;14)
    - `SCREENCAST - MLR - Part 6: making predictions <https://youtu.be/WSjfM4WPBBM>`_ (5:27)
* **3_ComparingCompetingModels_1_notes.Rmd** 
    - building and fitting linear models
    - interactions terms
    - using linear models for prediction
    - `SCREENCAST - Comparing models - metrics <https://youtu.be/ZClLyAmzx5g>`_ (5:18)
* **4_ComparingCompetingModels_2_notes.Rmd**
    - k-crossfold validation
    - comparison of performance on test data
    - `SCREENCAST - Comparing models - cross validation and predictive accuracy <https://youtu.be/Gdl5D3lmm90>`_ (23:59)
* **5_ResidualAnalysis_notes.Rmd**
    - normality of residuals
    - constantcy of variance
    - `SCREENCAST - Residual analysis <https://youtu.be/93L4tnudYr8>`_ (6:07)
* **6_MLB_regression_modeling_notes.Rmd**
    - build the best model you can
    - `SCREENCAST - Model building challenge <https://youtu.be/qt5zca_TeZo>`_ (12:18)


Explore (OPTIONAL)
==================

Regression modeling
-------------------

* `STAT 501 - Regression Modeling (Penn State Univ online) <https://onlinecourses.science.psu.edu/stat501/>`_ - Penn State has a bunch of free online resources for learning stats. 
* Regression modeling textbooks

   - `Regression and Other Stories <https://avehtari.github.io/ROS-Examples/>`_ (Gelman, Hill, Vehtari) Hot off the press. This book is about applied regression, uses R, and includes things like Bayesian approaches and using simulation.
   - `Applied Linear Statistical Models  <http://www.amazon.com/Applied-Linear-Statistical-Models-Michael/dp/007310874X/>`_ (Michael Kutner, Christopher Nachtsheim, John Neter , William Li) - A classic text. Well worth owning and studying.
   - `Linear Models with R  <http://www.amazon.com/Linear-Models-Chapman-Statistical-Science/dp/1584884258/>`_ (Faraway) A good R-centric book on linear modeling.
   - `Regression Modeling Strategies: With Applications to Linear Models, Logistic Regression, and Survival Analysis <http://www.amazon.com/Regression-Modeling-Strategies-Applications-Statistics/dp/1441929185/>`_ (Harrel) - I took a workshop given by Frank Harrel and have never looked at regression modeling quite the same. This is a very modern, more advanced look at applied regression modeling. Frank Harrel is a big "reproducible analysis" advocate, uses R, and is the author of several R packages.
   
* `Why every statistician should know about cross-validation <https://robjhyndman.com/hyndsight/crossvalidation/>`_

* StatQuest YouTube Channel - Josh Starmer
	- `StatQuest: P values, clearly explained <https://youtu.be/JQc3yx0-Q9E>`_
	- `StatQuest: Linear models (part 1) <https://www.youtube.com/watch?v=nk2CQITm_eo>`_
	- `StatQuest: Linear models (part 1.5) <https://www.youtube.com/watch?v=zITIFTsivN8>`_
	- `StatQuest: Linear models (part 2) <https://www.youtube.com/watch?v=NF5_btOaCig>`_
	- `StatQuest: Cross-validation <https://www.youtube.com/watch?v=fSytzGwwBVw>`_

General data science
--------------------
   
* `Field Guide to Data Science <https://www.boozallen.com/s/insight/publication/field-guide-to-data-science.html>`_ - Booz, Allen, Hamilton (one of the big consulting firms)
* Analytics jobs on the `KDnuggets jobs board <http://www.kdnuggets.com/jobs/index.html>`_- KDnuggets is a great site for all things analytics. Up until very recently it had an endearing design reminiscent of the early days of the web.
