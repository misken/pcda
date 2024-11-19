***********************************
Intro to R and R Studio
***********************************

In this module we will:

* get an overview of R and R Studio, 
* do basic interactive R tasks, 
* learn about R data types, installing packages, reading data into and working with dataframes,
* learn how to create and use basic R scripts to document a series of analysis steps,
* write our own "tutorials" or "learning guides" using the magic of R Markdown documents along with the knitr package. 
   
Readings
--------
* R for Everyone (RfE) - Chapters 1-6
* Practical Data Science with R (PDSwR) - Chapter 2
* See the `Additional Resources`_ section below, especially the stuff on asking good questions

Downloads
---------	
* `Download_IntroToR.zip <https://drive.google.com/file/d/1YnPqbSFNDYcavLQlrm8KLzi72FEcmLCp/view?usp=sharing>`_
* `R Markdown cheat sheet <http://www.rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf>`_ (R Studio)

Activities
---------------

We will work through a series of R scripts and R Markdown documents as
we start to learn the basics of R and R Studio. In the Downloads file
you'll find both "shell" versions of files that we'll fill in in class
as well as fully completed versions you can refer to later.

.. note::

    As of 2024-11-03, I have started replacing R Markdown documents with
    Quarto documents and updating the screencasts to reflect this change. Quarto
    is the future and it's time to move to it.

Overview of R 
^^^^^^^^^^^^^^
I'll use the slides for structure.

    - `SCREENCAST: Overview of R <https://youtu.be/Oqt1O2W_jqY>`_ (17:11)

The obligatory hello world example
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

We'll see a basic R script and learn how to run commands from it.
	
    * File: **HelloWorld.R** 
    * `SCREENCAST: HelloWorld.R <https://youtu.be/9aoAiv72cCE>`_ (8:34)


R Studio and Quarto
^^^^^^^^^^^^^^^^^^^^

Time to get familiar with working in R Studio with Quarto markdown documents. We'll go over:

    - R Studio interface
    - code chunks
    - basics of markdown

We'll use:
	
    - File: **interactive1_shell.qmd**
    - `SCREENCAST: Intro to R Studio and R Markdown  <https://youtu.be/EciNeDkWgyM>`_ (24:47)
    - `SCREENCAST: Installing and loading packages <https://youtu.be/1MLCk7mNQeU>`_ (7:05)
    - `SCREENCAST: Interactive computing with R <https://youtu.be/_6mxc2XKzjA>`_ (23:03)
	
Vectors
^^^^^^^^
Vectors are a fundamental data structure in R. We need to start
thinking in vectors.

    * File: **vectors_shell.qmd**
    * `SCREENCAST: R Vectors <https://youtu.be/AXKJjGkzZ5A>`_ (21:17)
	
Dataframes
^^^^^^^^^^^
Dataframes are the primary data structure in R. You can think of them kind of
like a table in a database or a spreadsheet.

    * File: **dataframes_shell.qmd**
    * `SCREENCAST: R Dataframes <https://youtu.be/tZgbtBsKP_0>`_ (10:27)
	
Reading text files into R dataframes
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
This is a fundamental R task and we'll get our first look at it here. We will
also see an example of bringing data in R from a database.

    * File: **readcsv_shell.qmd**
    * `SCREENCAST: Intro to Getting Data into R <https://youtu.be/7XbwXjZ6W_U>`_ (14:28)
	
    .. note::
	The default for ``stringsAsFactors`` was changed to FALSE in R 4.0. Strings as factors as FALSE for the default is particularly nice when you are reading in some table that has string fields with a gagillion unique values that you would never use as a factor. You'll see that in many vids we do some string to factor work with ``as.factor()``. For me personally, I don't have a strong opinion as to whether the default should be TRUE or FALSE, just that it's important to understand what the default is if you are using ``read.csv`` or ``read_csv`` from the readr package. Then you just adapt on the fly and set it to whatever makes the most sense for the specific data set you are reading. 


Datetime conversions
^^^^^^^^^^^^^^^^^^^^^	
	
This last Rmd file has some additional details on datetime conversions.
Dates and times can be tricky and we'll learn about converting between character and datetime data types

    * File: **chardate_POSIXct_conversion.Rmd**




Additional Resources
---------------------

`Jenny Bryan <https://jennybryan.org/about/>`_ developed and taught R related courses at
the University of British Columbia. In particular, she was the driving
force behind a course called `STAT 545 <https://stat545.com/>`_ and an `online textbook <https://stat545.com/index.html>`_. Now she works at Posit on Hadley Wickham's team, but her course lives on. Many of the resources
she created for STAT 545 are still available and will continue to 
evolve. I highly recommend them as they really get at the heart of
effectively using R to do analysis. It also includes invaluable practical R related information that
is rarely found all in one place. Highly recommended.

Asking good questions
^^^^^^^^^^^^^^^^^^^^^

One particularly helpful page Jenny Bryan created in the old 545 course was
one on "How to get unstuck". Unfortunately, while the new course website
includes a link to it, the link is broken. Using the magical wayback machine
I was able to locate an archived copy which I'm including here until the
link gets fixed. One of the resources she links to in her "unstuck"
page is a classic document entitled "How to Ask Questions the Smart Way" by
Eric Raymond and Rick Moen. It
is not for the easily offended, but as Jenny says, they "speak truth". 

* `How to get unstuck <https://web.archive.org/web/20190318100139/http://stat545.com/help-general.html>`_ 
* `How to write a great online question <https://www.dataschool.io/how-to-ask-for-coding-help-online/>`_ - great advice from Kevin Markham at Data School
* `How to Ask Questions the Smart Way <http://www.catb.org/~esr/faqs/smart-questions.html>`_ 

Reproducible examples (reprex)
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

A big part of asking good questions is creating something known as a minimal reproducible example, or *reprex* for short.
When people post questions to places like StackOverflow or a GitHub Issue they are **strongly** encouraged
(in SO it's almost a must) to include a reprex. There's a very good `FAQ entry in the R Studio 
Community Forum <https://community.rstudio.com/t/faq-whats-a-reproducible-example-reprex-and-how-do-i-create-one/5219>`_ that discusses the reprex in both general terms and provides links the `R reprex package <https://reprex.tidyverse.org/index.html>`_ which makes it easy
to create a reprex that can be pasted from the clipboard into a question or forum.

* `How to use reprex <https://reprex.tidyverse.org/articles/learn-reprex.html>`_
* `Ask Better Code Questions (and Get Better Answers) With Reprex <https://data.library.virginia.edu/ask-better-code-questions-and-get-better-answers-with-reprex/>`_

DataCamp
^^^^^^^^^^

There's an `Intro to R course at DataCamp <https://www.datacamp.com/courses/free-introduction-to-r>`_ that covers much of what we do in
this first session. There are `many R courses <https://www.datacamp.com/search?q=r>`_ available on DataCamp.

Explore
--------

* `R-bloggers <http://www.r-bloggers.com/>`_ - Aggregation site for R related blogs
* `Simply Statistics <http://simplystatistics.org/>`_ - Roger Peng and two other biostats guys from Johns Hopkins blog on data science and R. Peng has a super popular online R course through Coursera and these folks have launched a several course series on data science in R on Coursera.
* `Introducing R to a non-programmer in one hour <http://alyssafrazee.com/introducing-R.html>`_ - Just what it says. 
* `R vs Python for Data Science: Summary of Modern Advances <https://elitedatascience.com/r-vs-python-for-data-science>`_




