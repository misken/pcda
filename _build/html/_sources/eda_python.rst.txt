*****************************************************
Data analysis and plotting in Python
*****************************************************

Intro and Objectives
====================

`Pandas <http://pandas.pydata.org/>`_, developed by Wes McKinney, is the "go to" library for doing data manipulation and analysis in Python. It's not really a statistics library (ala R); for that, `StatsModels <http://statsmodels.sourceforge.net/>`_ is the Python library of choice for now. For more advanced stuff like machine learning and data mining algorithms, `scikit-learn <http://scikit-learn.org/stable/>`_ is the go to Python module.

The de-facto standard plotting library for Python is called `matplotlib <http://matplotlib.org/>`_ and it's one of the key reasons that Python has become such a major force in the analytics world. Below, you'll also find information on `Seaborn <https://stanford.edu/~mwaskom/software/seaborn/>`_, a newish plotting package that uses matplotlib under the hood but provides an easier to use high level interface for common plotting tasks. Another option for visualization is `Bokeh <http://bokeh.pydata.org/en/latest/>`_ it's designed for creating interactive graphs using web browsers for presentation. `Plotly <https://plotly.com/python/>`_ also has similar tools for interactive, web based, Python plotting.
   
Readings
========

Python Data Science Handbook (PDSH)  - Ch 3 is on pandas, Ch 4 is matplotlib 

Downloads and other resources
=============================

* `Downloads_pandas_matplotlib_intro.zip <https://drive.google.com/file/d/14KXn3ynHSPran1DJIZvrRQ0qtD8f9vJy/view?usp=sharing>`_
* `Jupyter notebooks for Python Data Science Handbook <https://github.com/jakevdp/PythonDataScienceHandbook>`_ - JVPs GitHub site has the full text of the book within Jupyter notebooks. Makes it super easy for self-study.


Activities
================================

Start with this intro to the session: `SCREENCAST: Overview of session <https://youtu.be/8zjV0gm71Gg>`_

This is the primary notebook that we'll use to learn the basics of pandas and matplotlib. We'll also be looking at a few of JVP's notebooks on matplotlib.

* **ORSchedLeadTime_Python.ipynb** in ORSchedLeadTime_Python/

Clear the output before starting. This notebook covers the basics of pandas and matplotlib. 

    - `SCREENCAST: Intro to pandas/matplotlib - Part 1 - data structures <https://youtu.be/zklq_e0GLJ0>`_ (17:21)
    - `SCREENCAST: Intro to pandas/matplotlib - Part 2 - indexing with iloc() and loc() <https://youtu.be/5C09mGarbtk>`_ (12:47)
    - `SCREENCAST: Intro to pandas/matplotlib - Part 3 - matplotlib <https://youtu.be/RHYPNINmpGc>`_ (23:07)
    - `SCREENCAST: Intro to pandas/matplotlib - Part 4 - group by analysis <https://youtu.be/NcsFkehgYw8>`_ (7:44)

    

* **c19_data_wrangle_viz.ipynb** in c19_data_wrangle_viz/

    - `SCREENCAST: Processing/plotting Covid-19 data with pandas, matplotlib and Seaborn <https://youtu.be/u2rEwmaYqAs>`_ (31:29)

Back in April 2020, I developed a Jupyter notebook to automate the process of downloading and processing daily Covid-19 case data. The processing steps included adding new fields, reshaping to make plotting easier and just organizing the data in a way that facilitated analysis. Finally, the notebook produced faceted plots of cases by county in the state of Michigan and by state for the entire US. The plotting is done using matplotlib and Seaborn. I've adapted that notebook for use in this class by cleaning things up and adding a large amount of explanatory text. This is a good example of a very real use of Python for data analysis and includes more advanced things than done in the first introductory notebook.

.. note::
    
	Before launching Jupyter lab do a ``conda activate datasci`` so that you can pip install the `us <https://pypi.org/project/us/>`_ package. It's really useful package for working with things like state abbreviations and FIPS codes.

You can pip install it:

.. code-block::
   
    $ conda activate datasci
    $ pip install us
    $ conda deactivate
    $ jupyter lab
    
Now you can go through the **c19_data_wrangle_viz.ipynb** notebook.

Optional activities
-------------------

Here are some additional notebooks that you can check out if you are interested in the topic.

* **Visualization_Techniques_Seaborn.ipynb** in Final_Project_SeabornPlotting/

    - Seaborn is a newish visualization library built on top of matplotlib
    - this is a student final project
    
* **pandas_ch2_movielens.ipynb** in movielens/

    - based on Ch2 of Wes McKinney's Pandas book
    - shows table merging and pointers to other pandas tutorials from SQL point of view
    
* **datetime_exploring.ipynb** in datetime/

    - Python has terrific libraries for dealing with time series (pandas). However, there be dragons in the confluence of pandas, numpy, and base Python date and time handling. Given the ubiquitous nature of datetime data in business, slaying these dragons is a calling we cannot avoid. I cover this topic is quite a bit of detail in my MIS 4900/6900 - Advanced Analytics with Python course. You can find the full set of datetime related subtopics and screencasts at `http://www.sba.oakland.edu/faculty/isken/courses/mis6900_s21/datetime_occupancy.html <http://www.sba.oakland.edu/faculty/isken/courses/mis6900_s21/datetime_occupancy.html>`_
	
* **templogger_batch.py** in temp_logging_pcda/

    - Short focused example of using pandas and matplotlib for automated data processing
    - includes file globbing

Explore (Optional)
==================

Pandas
------

* `Learn-Pandas GitHub repo (Ted Petrou) <https://github.com/tdpetrou/Learn-Pandas>`_ - thorough, well done, coverage of pandas via a series of Jupyter notebooks
* `Top 8 resources for leaning data analysis with pandas <http://www.dataschool.io/best-python-pandas-resources/>`_
* `Tidyverse pipes in pandas <https://stmorse.github.io/journal/tidyverse-style-pandas.html>`_- if you like pipes in dplyr, check out how you can do similar things in pandas
* `Guide to encoding categorical values in Python <http://pbpython.com/categorical-encoding.html>`_

* `Working with SQLite databases using Python and Pandas <https://www.dataquest.io/blog/python-pandas-databases/>`_

* `7 steps to mastering SQL for data science <https://www.kdnuggets.com/2016/06/seven-steps-mastering-sql-data-science.html>`_

Visualization
--------------
* `Python Charts <https://python-charts.com/>`_
* `Python data viz cookbook <https://dataviz.dylancastillo.co/>`_ - nice little interactive web site for generating common plots in pandas, matplotlib, Seaborn, and plotly.
* `Effectively using matplotlib <https://pbpython.com/effective-matplotlib.html>`_
* `Python plotting with matplotlib <https://realpython.com/python-matplotlib-guide/>`_
* `Seaborn: statistical visualization <http://stanford.edu/~mwaskom/software/seaborn/introduction.html>`_

    Seaborn is a library for making attractive and informative statistical graphics in Python. It is built on top of matplotlib and tightly integrated with the PyData stack, including support for numpy and pandas data structures and statistical routines from scipy and statsmodels. Some of the features that seaborn offers are

        - Several built-in themes that improve on the default matplotlib aesthetics
        - Tools for choosing color palettes to make beautiful plots that reveal patterns in your data
        - Functions for visualizing univariate and bivariate distributions or for comparing them between subsets of data
        - Tools that fit and visualize linear regression models for different kinds of independent and dependent variables
        - Functions that visualize matrices of data and use clustering algorithms to discover structure in those matrices
        - A function to plot statistical timeseries data with flexible estimation and representation of uncertainty around the estimate
        - High-level abstractions for structuring grids of plots that let you easily build complex visualizations

* `Modern Pandas: Visualization <http://tomaugspurger.github.io/modern-6-visualization.html>`_ This is actually Part 6 of a series of blog posts on modern use of pandas. It gives a good overview of the landscape of Python plotting with matplotlib, pandas, and Seaborn and focuses on how Seaborn is a great direction for those looking for a plotting package that supports exploratory data analysis.
* `The magic of matplotlib stylesheets <https://www.datafantic.com/the-magic-of-matplotlib-stylesheets/>`_


Applications
-------------

* `Introduction to stock market data analysis with Python <https://ntguardian.wordpress.com/2018/07/17/stock-data-analysis-python-v2/>`_
* `Hillmaker - an occupancy analysis tool <https://github.com/misken/hillmaker>`_ - If anyone is interested, there are a few things one could do for the class project that would involve contributing to this open source project. I'm the developer. Take a look and if interested, let me know and I can describe some project options.
* `Kaggle: Example analysis of the SNL database <https://www.kaggle.com/hhllcks/example-analysis-of-the-snl-database>`_ - Kaggle is a great place to find datasets, sample analyses and competitions related to data science. You'll need an account for this class anyway.


