***********************************
EDA with R 
***********************************

.. note::
    The notes for this session have been updated to use Quarto instead of R Markdown. You can find the `old version here <https://pcda.misken.org/eda_r>`_

Intro and Objectives
--------------------

We will begin to do exploratory data analysis in R. After completing
the activities in this module, you should be able to explore a 
dataset using:

* descriptive statistics,
* simple R scripts including writing your own functions, 
* basic (and not so basic) plots with ggplot2. 


We are going to explore a dataset related to New York City condo evaluations for fiscal year 2011-2012. It was obtained
from the NYC Open Data initiative - https://data.cityofnewyork.us/. 
   
Readings
---------

* I2R - Chapters 4-7
* R4DS - Chapters 1-2

Downloads and other resources
-----------------------------

* `Downloads_EDA1withR.zip <https://drive.google.com/file/d/1TpCepJFGaCDIyhSxF017VezO2xCueH8n/view?usp=sharing>`_

Other Resources:

* `Data files for the "R for Everyone" text <https://www.jaredlander.com/data/>`_
* `ggplot2 cheat sheet <https://github.com/rstudio/cheatsheets/blob/master/data-visualization-2.1.pdf>`_ (R Studio)
* `Hadley Wickham is working on a new ggplot2 book <https://ggplot2-book.org/>`_

Activities
-----------

We will work through two tutorials on EDA (with a short detour on
creating user defined functions in R)

Summary statistics
^^^^^^^^^^^^^^^^^^
R makes it easy to compute summary statistics. We will also see how to 
create R Projects to help you organize your R work.

    * File: **EDA1a_summarystats_shell.qmd**
    * `SCREENCAST: Overview of EDA and creating R Project <https://youtu.be/ikW7GHwjFWo>`_ (8:30)
    * `SCREENCAST: Inital exploration of housing dataframe <https://youtu.be/gcFRacvr9CY>`_ (11:21)
    * `SCREENCAST: Modify dataframe, summary statistics, save as binary file <https://youtu.be/kLTASLL2lzQ>`_ (22:24)

Writing your own functions
^^^^^^^^^^^^^^^^^^^^^^^^^^^
We will do a brief introduction to writing functions in R.

* File: **summarystats_4470.R**
* `SCREENCAST: Create your own R function <https://youtu.be/0huJzAyDi4c>`_ (12:40)

.. note::
    The video above makes a few references to the "R for Everyone" text that
	we are not longer using. Instead, see Chapter 7 of the
	` An Introduction to R <https://intro2r.com/>`_ online textbook.
	
Plots and graphs
^^^^^^^^^^^^^^^^^
Now we are going to see an area where R really shines - plotting.

    - File: **EDA1b_basicplots_shell.qmd**
    - `SCREENCAST: Intro to data visualization and base plot <https://youtu.be/UVvp7h17FdI>`_ (9:35)
    - `SCREENCAST: Intro to ggplot2 and the Grammar of Graphics <https://youtu.be/XeAvGtKNmPg>`_ (14:53)
    - `SCREENCAST: Histograms, boxplots and violin plots, faceting and reusing plot objects <https://youtu.be/l-yfXzmxihc>`_ (11:17)
    - `SCREENCAST: Scatter plots <https://youtu.be/h5nO5n3cWQ0>`_ (3:11)
    - `SCREENCAST: Themes <https://youtu.be/LR9Rz7fvjVY>`_ (6:37)
    - `SCREENCAST: Density plots and other histogram alternatives <https://youtu.be/JxCB1vBi4Qc>`_ (5:30)
    - `SCREENCAST: Bar charts <https://youtu.be/LMCmSn0LdLw>`_ (6:54)
    - `SCREENCAST: Correlation plots and Geeky fun with xkcd <https://youtu.be/a8hJmZoBtCA>`_ (7:10)

Explore (OPTIONAL)
------------------

* `A framework for exploratory data analysis <https://github.com/ojedatony1616/exploratory_transformation/blob/master/transformation.pdf>`_ - As you browse this, there's a "More Pages" button at the bottom. You can also download the pdf from the GitHub site.

Data visualization
^^^^^^^^^^^^^^^^^^^

* There's no doubt that ggplot is awesome, but `check out what can be done if you have a good grasp of base plotting in R <https://github.com/karoliskoncevicius/tutorial_r_introduction/blob/main/baseplotting.md>`_. When I read this, it felt a bit like matplotlib, the venerable Python based plotting package.
* `R Graph Catalog <https://r-graph-gallery.com/>`_ Plot demos and code
* `Data visualization Cheet Sheet from R Studio <https://www.rstudio.com/resources/cheatsheets/#ggplot2>`_
* `Box plot comic <https://xkcd.com/1798/>`_ - You can always count on xkcd.
* `Some data visualization resources from my MIS 5460: Business Analytics class <http://www.sba.oakland.edu/faculty/isken/courses/ba/data_viz.html>`_
* `R Shiny app for visualizing NYC bike share data <https://nycdatascience.com/blog/student-works/r-visualization/nyc-citi-bike-migration-visulization/>`_- Lots of interesting logistical challenges with bike share programs. EDA plays a role in gaining insight to system dynamics. 



R Markdown
^^^^^^^^^^^

* Now that you know some basic R Markdown, you might want to dig into its capabilities a little further. This `overview provided by the folks at R Studio <http://rmarkdown.rstudio.com/>`_ is a good place to start. In addition, Ch 27-28 of RforE covers R Markdown, knitr, and LaTex.
* `Daring Fireball: Markown Syntax site <https://daringfireball.net/projects/markdown/syntax>`_ - This is John Gruber's site - he developed Markdown. 
* `Tips and tricks for working with images and figures in R Markdown documents <http://www.zevross.com/blog/2017/06/19/tips-and-tricks-for-working-with-images-and-figures-in-r-markdown-documents/>`_ - Very comprehensive post on the ins and outs of working with both external images as well as R generated images within R Markdown documents.

Percentiles
^^^^^^^^^^^^^
It's easy to get enamored with averages. They don't tell the whole story. Look at percentiles, too.

* Examples of why percentiles are important for performance monitoring by `Dynatrace <https://www.dynatrace.com/news/blog/why-averages-suck-and-percentiles-are-great/>`_, `Elastic <https://www.elastic.co/blog/averages-can-dangerous-use-percentile>`_, `AppSignal <https://blog.appsignal.com/2018/12/04/dont-be-mean-statistical-means-and-percentiles-101.html>`_ and `Optimizely <https://www.optimizely.com/insights/blog/why-cdn-balancing/>`_.
* `Percentiles in PostgreSQL <https://blog.timescale.com/blog/how-percentile-approximation-works-and-why-its-more-useful-than-averages/>`_ - this SQL flavor has implemented some nice percentile and `time weighted stats functions <https://blog.timescale.com/blog/what-time-weighted-averages-are-and-why-you-should-care/>`_, including approximate percentiles.









