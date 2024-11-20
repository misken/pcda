************************************************************************************
Modeling 1: Overview and linear regression in R with tidymodels (UNDER CONSTRUCTION)
************************************************************************************

**NOTE: This is new material for Winter 2025**

Intro and Objectives
====================

One of the workhorses of statistical predictive modeling is the family of linear models. We'll do things like multiple linear regression for numeric predictions and logistic regression as a classifier for binary response variables. We'll use these relatively simple models as a way to also learn about important modeling topics such as partitioning data into training and test sets, model training, validation and diagnostics. We'll also use regression to introduce the notion of parameter estimation, error metrics for assessing model fit and for comparing candidate models against each other. These topics underlie all of statistical learning algorithms. 
   
Readings
========

* ISLR - Ch 1-3 and 4.1-4.3

`An Introduction to Statistical Learning with applications in R <https://statlearning.com/>`_

This is an outstanding book, which is available as a free pdf. ISLR covers the main statistical learning topics at a nice introductory level. 

I will be listing the associated reading that you can do from ISLR as we explore various statistical learning topics - starting with linear regression.

* `In-depth introduction to machine learning in 15 hours of expert videos <https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/>`_ - The ISLR authors have created a whole series of video lectures based on their book.

* `Tidy Modeling with R <https://www.tmwr.org/>`_ - Ch 4-11
* `ISLR Tidymodels labs <https://emilhvitfeldt.github.io/ISLR-tidymodels-labs/03-linear-regression.html>`_ - Ch 3 (Linear regression)

Downloads and other resources
=============================

* `Downloads_StatModels1_tidymodels.zip <https://drive.google.com/file/d/1Tce4bXgYPAVCsAPnNQZFj4aNPvXsFEHy/view?usp=drive_link>`_

If you are rusty on statistics, there's a really good OpenIntro Stats book available as a free online book or you can pay what you want for a paperback copy. It includes R based material.

* `OpenIntro Stats <https://www.openintro.org/book/ims/>`_

Activities
================================

We are going to work through a series of tutorials exploring the topic
of building, using and evaluating predictive linear regression models.

    * `SCREENCAST - Overview of statistical modeling session <https://coming_soon>`_ (5:32)

Next we'll do a brief review of working with probability distributions in R.

    * File: **0_probability_dists.qmd**
    * `SCREENCAST - Probability distributions in R <https://coming_soon>`_ (5:44)

Review of simple linear regression of will set the stage for
more complex linear models.

    * File: **1_simple_linear_regression.qmd**
    * `SCREENCAST - Simple linear regression <https://coming_soon>`_ (20:45)

Now we are ready for multiple linear regression. In this part, we will use
the built in `lm()` function for fitting linear models. We will deal with
missing data, partition data into training and test datasets, build and fit linear models with ``lm()``, assess model fit, make predictions and assess
predictive accuracy of our models using simple techniques.

    * File: **2_multiple_linear_regression.qmd**
    * `SCREENCAST - MLR - Part 1: imputation of missing values <https://coming_soon>`_ (5:39)
    * `SCREENCAST - MLR - Part 2: partition into train and test <https://coming_soon>`_ (2:47)
    * `SCREENCAST - MLR - Part 3: some EDA <https://coming_soon>`_ (4:10)
    * `SCREENCAST - MLR - Part 4: fitting simple additive models <https://coming_soon>`_ (6:36)
    * `SCREENCAST - MLR - Part 5: fitting models with interaction terms <https://coming_soon>`_ (4;14)
    * `SCREENCAST - MLR - Part 6: making predictions <https://coming_soon>`_ (5:27)
	
There are better (or at least, newer) ways to build and compare models in R. 
We'll use the tidymodels package to do similar things that we just did.
	
    * File: **3_comparing_competing_models.qmd** 
    * `SCREENCAST - Intro to tidymodels <https://coming soon>`_ (5:18)
    * `SCREENCAST - Data partitioning <https://coming soon>`_ (5:18)
    * `SCREENCAST - Model fitting with parsnip <https://coming soon>`_ (5:18)
    * `SCREENCAST - Computing error metrics <https://coming soon>`_ (5:18)
    * `SCREENCAST - Comparing models with cross-validation <https://coming soon>`_ (5:18)
    * `SCREENCAST - Assessing predictive performance <https://coming soon>`_ (5:18)

Explore (OPTIONAL)
==================

Regression modeling
-------------------

* `STAT 501 - Regression Modeling (Penn State Univ online) <https://online.stat.psu.edu/stat501/>`_ - Penn State has a bunch of free online resources for learning stats. 
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

