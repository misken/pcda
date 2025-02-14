****************************************************************
Group by analysis and data wrangling with R 
****************************************************************

.. note::
    The notes for this session have been updated to use Quarto instead of R Markdown. You can find the `old version here <https://pcda.misken.org/data_wrangling_r>`_.

Intro and Objectives
--------------------

The term data wrangling is used to describe the process of reading, exploring, cleaning, and transforming data in preparation for modeling, statistics and machine learning. A popular rule of thumb is that you'll typically spend 80% of total project time on data wrangling! Having done analytics work professionally both in industry and academia, this rings true. Getting good at data wrangling will pay off big time. We'll start with basic wrangling tasks using R. Later in the semester we'll revisit wrangling with Python and learn some more advanced methods. This does NOT mean that R can't do the wrangling things that Python can - it can. It just makes sense to save some of the more advanced stuff like regex, JSON and web scraping until we get to Python. This will allow us to get going quicker doing statistical modeling in R.  Common data wrangling tasks such as dealing with missing data and feature engineering will pop up over and over again as we get into statistical learning models.Some of the things we'll do include:

* We'll learn about various ways to do "pivot" or "group by analysis" with a focus on the widely used dplyr package (more Hadley Wickham creations) - though I'll also introduce classic R techniques using the ``apply`` family of functions.
* reading csv, Excel, and SQLite data into R,
* string and date/time manipulation for cleaning/transforming data,
* tidying and reshaping data,
* saving/writing data.
   
Readings
--------

* R4DS - 5, 7, 14, 17, 19, 20, 21

Downloads and other resources
------------------------------

* `Downloads_EDA2withR.zip <https://drive.google.com/file/d/1fmlP-7M5ZIrXnl758TdYr3-LRquZGAZz/view?usp=sharing>`_ - Group by analysis using old school tools like apply along with new era tools such as plyr and dplyr. Basic date/time manipulation.
* `Downloads_DataWranglngwithR.zip <https://drive.google.com/file/d/1dcMv6dDsTLaduOzuu49_2PS9IbX0OEPT/view?usp=sharing>`_ - More on getting data into and out of R. Also, data reshaping and basic string manipulation.
* `Data wrangling (dplyr and tidyr) cheat sheet <http://www.rstudio.com/wp-content/uploads/2015/02/data-wrangling-cheatsheet.pdf>`_ (R Studio)

Activities
-----------
We will do a few different data wrangling things in this session.

Group by analysis with dplyr
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Tools like Excel Pivot Tables and aggregate SQL queries are commonly used for what
is known as "group by" analysis.

We'll start by learning about the new dplyr library - think pivot tables but way more powerful.

Here's the file we'll be using.
 
* File: **dplyr_basics_shell.qmd**

I'm going to break this up into logical chunks.

* `SCREENCAST: Intro to group by analysis with dplyr <https://youtu.be/rdDEvcnywL8>`_ (13:50)
* `SCREENCAST: Using filter() to get subset of rows <https://youtu.be/ZXO1T_eKHmo>`_ (8:38)
* `SCREENCAST: Using select() to get subset of columns <https://youtu.be/tQQalylyoDk>`_ (3:04)
* `SCREENCAST: Using mutate() to compute new variables <https://youtu.be/Ukz5qNEHRyk>`_ (9:15)
* `SCREENCAST: Using summarise() to do aggregations like sums, counts, means, ... <https://youtu.be/Jul8bKUGqho>`_ (19:48)
* `SCREENCAST: Using dplyr with databases <https://youtu.be/NNAk4I-L1Ic>`_ (10:03)

Ingesting data and saving data
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Now let's see some alternatives to ``read.table`` and ``read.csv``, a bit on tibbles, RData and RDS files, built in datasets. 

* File **data_wrangling_ingesting.qmd**
* `SCREENCAST: Getting data into R <https://youtu.be/D_A6lX6TW58>`_ (10:04)

Combining data
^^^^^^^^^^^^^^^

Let's learn about combining data by rows and columns as well as doing SQL style joins. 

* File: **data_wrangling_combining_notes.qmd**
* `SCREENCAST: Combining data <https://youtu.be/jmh3QI-Uz9A>`_ (22:01)

Reshaping data
^^^^^^^^^^^^^^^

The tidyverse approach to reshaping data between long and wide formats is next. 

* File: **data_wrangling_reshaping_notes.qmd**
* `SCREENCAST: Wide <--> Long with tidyr <https://youtu.be/YiMtRXM46XA>`_ (12:43)

Older material (OPTIONAL)
^^^^^^^^^^^^^^^^^^^^^^^^^^

If you have the time and interest, check out
the "old school" approach use base R tools such as the apply family
of functions as well as a tool called plyr. 

* File **GroupByAnalysis_oldschool_notes.Rmd** (OPTIONAL)

Prior to the tidyverse, the reshape2 package was used to go between wide and long data formats. Then tidyr came along. The next screencast uses reshape2. It also gets into some basic string manipulation like substringing as well as some more advanced ggplot2 plot formatting. 

* File: **DataWrangling_reshaping_pretidy_notes.Rmd**
* `SCREENCAST (OPTIONAL): Wide <--> Long with reshape2 (melt and cast) <https://youtu.be/d00MoWdb7LQ>`_ (17:44)



Explore (OPTIONAL)
------------------

Split-Apply-Combine
^^^^^^^^^^^^^^^^^^^^

* `The Split-Apply-Combine Strategy for Data Analysis <https://www.jstatsoft.org/article/view/v040i01>`_ - This is the original paper by Hadley Wickham. I've also included the pdf in the Downloads file for this session.
* `A brief introduction to “apply” in R <http://nsaunders.wordpress.com/2010/08/20/a-brief-introduction-to-apply-in-r/>`_ - This is one of the best overviews I've found of the "apply" family of functions in R.
* `Introduction to dplyr for Faster Data Manipulation in R <https://rpubs.com/justmarkham/dplyr-tutorial>`_ - Very good dplyr tutorial by Kevin Markham.


Data reshaping
^^^^^^^^^^^^^^^^

* `Tidy Data <https://www.jstatsoft.org/article/view/v059i10/v59i10.pdf>`_ - This is the original paper by Hadley Wickham.
