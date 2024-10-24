Resource Center
===============

Here a links to a variety of data science and business analytics related resources.

General business analytics, data science, statistical modeling
---------------------------------------------------------------

* `Analytics Magazine`_ It's published by `INFORMS - the Institute for Operations Research and Management Science <https://www.informs.org/>`_. They are the premier professional society for analytics and it's inexpensive to join as a student. Full disclosure, I've been an INFORMS member since about 1986 (when it was still ORSA/TIMS). We were doing analytics before it was called analytics. :)
* `Data science - A first introduction <https://datasciencebook.ca/>`_ - nice online and free text that gets you going with data science using R and the tidyverse by a collection of faculty at the University of British Columbia
* `Awesome Data Science <https://github.com/bulutyazilim/awesome-datascience>`_ - giant curated list of data science resources
* `Statistical Modeling, Causal Inference, and Social Science <https://statmodeling.stat.columbia.edu/>`_ - Andrew Gelman's very high quality blog. Lots of stuff on doing stats correctly.	
* `Statistical Modeling: The Two Cultures <Statistical Modeling, Causal Inference, and Social Science>`_ - paper by L. Breiman (2001) that gets at the heart of the statistics vs ML tension.
* `Open data science curriculum <https://github.com/ossu/data-science>`_ - collection of free courses on various data science, math and stat topics

Careers
--------

* There are numerous groups on Reddit related to analytics and data science. These can be very good resources for unvarnished conversations/opinions about careers, grad school as well as technical advice.
    - `r/datascience <https://www.reddit.com/r/datascience/>`_
    - `r/analytics <https://www.reddit.com/r/analytics/>`_
    - `r/OperationsResearch <https://www.reddit.com/r/OperationsResearch/>`_
    - `r/BusinessIntelligence <https://www.reddit.com/r/BusinessIntelligence/>`_
    - `r/DataEngineering <https://www.reddit.com/r/dataengineering/>`_
	
* `December 2022: Data Science Career Resources <https://dspn.substack.com/p/december-2022-data-science-career>`_ and `Essay on data science hiring process <https://ericmjl.github.io/essays-on-data-science/people-skills/hiring>`_ by Eric Ma who writes the Data Science Programming Newsletter on Substack.


Programming tutorial hubs
--------------------------
* `Software Carpentry <https://software-carpentry.org/lessons/>`_ and `Data Carpentry <https://datacarpentry.org/lessons/>`_ - helping scientists learn to do computational work with R, Python, SQL and other tools
* `Real Python <https://realpython.com/>`_



Online courses
---------------

There are numerous online courses available through DataCamp, Coursera, EdX, Udemy and others. Here's a few Python and R ones I've checked out over the years.

* `Intro to Data Science in Python`_ - I did this short course in Feb 2017 (Coursera UMich). Great fun.  If you want a good pandas/python learning challenge, try the assignments.
* `Python for Everybody course`_ - This site includes a bunch of videos and  supplementary files. The whole thing was created by a professor at  University of Michigan and is meant to be a totally open set of freely available learning materials for Python in the context of data analysis.
* Coursera has some well regarded `R based data science courses <https://www.coursera.org/specializations/data-science-foundations-r>`_

Learning the command line
--------------------------

As you've no doubt gathered from this class, I'm a big fan of using the command line for certain data related tasks and think that command line skills are really important. There's a new 2e of the O'Reilly book "Data science at the command line". The second edition is FREELY available online.

https://datascienceatthecommandline.com/ - home page for the book

https://datascienceatthecommandline.com/2e/ - the free 2nd edition

Chapter 1 is a great overview of why you should become adept at using the command line.

Learning R
----------

Online R tutorials, books and examples for getting started
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `R-bloggers`_- The aggregator for R related blogs.
* `R for Data Science`_ - Free, online version of the book, **R for Data Science** by Hadley Wickham and Garrett Grolemund.
* `Quick-R`_ - This is a great site dedicated to helping R newbies get over the somewhat steep R learning curve.
* `fasteR: The fast lane to learning R <https://github.com/matloff/fasteR>`_ - created by Norm Matloff who is a big proponent of learning base R first before doing things with tidyverse packages.
* `STAT 545 - Data wrangling, exploration, and analysis with R <https://stat545.com/>`_ - Jenny Bryan's course developed at UBC and still used even though JB has moved on to R Studio. Not only does this cover R, but also gets into things like version control, web scraping and Shiny.
* `Cookbook for R`_ - Another great site for learning R. In their words: "The goal of the cookbook is to provide solutions to common tasks and problems in analyzing data."
* `Webinars from R Studio`_- The creators of the hugely popular R Studio package have a ton of learning resources on their site.
* `The Official R Manuals`_ - These are accessible from the main R Project page in the Documentation section.
* `Contributed Documentation`_ - Many people have written tutorials, books, and other free documentation for various aspects of R. This is part of the magic of R community.
* `Introducing R to a non-programmer in one hour`_ - Just what it says.
* `Teach yourself Shiny`_- A somewhat recent development by the folks at R Studio is something  called a Shiny web app. Learn to create interactive, R driven, web apps!

The base R vs tidyverse debate
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The tidyverse has become increasingly popular and with this popularity has come more scrutiny. In particular,
there's a healthy debate on whether new R users should first learn base R and then move on to the tidyverse or
whether they should immediately be taught the tidyverse approach. It really isn't an either-or question and
in this course you will both base R and tidyverse approaches. I do start with base R because I think you
need a good understanding of things like vectors to make the most of the R language. At the end of the day,
we use R to solve problems and the more tools you have to tackle those problems, the better off you will be.
A few good resources on this debate include the following.

* The `TidyverseSkeptic <https://github.com/matloff/TidyverseSkeptic>`_ project by Norm Matloff (his fasteR project is described above) is a well known essay on why new R learners should be taught base R first. Check out the Issues for some heated discussion.
* David Robinson argues the tidyverse first side in posts such as http://varianceexplained.org/r/teach-tidyverse/ and http://varianceexplained.org/r/why-I-use-ggplot2/. (yes, technically ggplot2 predates the tidyverse).
* Data Carpentry has a post on `base R and tidy equivalents <https://tavareshugo.github.io/data_carpentry_extras/base-r_tidyverse_equivalents/base-r_tidyverse_equivalents.html>`_
* Caret vs tidymodels also (kinda) falls into this debate - see `On not using tidymodels <https://staffblogs.le.ac.uk/teachingr/2020/10/05/on-not-using-tidymodels/>`_, and `Caret vs tidymodels: the old and the new <https://konradsemsch.netlify.app/2019/08/caret-vs-tidymodels-comparing-the-old-and-new/>`_, and `this Reddit post <https://www.reddit.com/r/Rlanguage/comments/etg25g/should_i_learn_caret_or_tidymodels/>`_.
* One criticism of the tidyverse is that it can lead to dependency bloat - learn more from `this essay <https://www.tinyverse.org/>`_ about the "tinyverse".
* I did a `short blog post on base vs tidy <https://misken.github.io/blog/base_v_tidy/>`_
* There's no doubt that ggplot is awesome, but `check out what can be done if you have a good grasp of base plotting in R <https://github.com/karoliskoncevicius/tutorial_r_introduction/blob/main/baseplotting.md>`_. When I read this, it felt a bit like matplotlib, the venerable Python based plotting package.
* There are a few Reddit threads that address this topic including `this one <https://www.reddit.com/r/rprogramming/comments/ondo0y/what_do_you_think_of_r_beginners_learning/>`_ and `this other one <https://www.reddit.com/r/rprogramming/comments/rd4ksl/i_am_concerned_about_the_tidyverse_and_its_impact/>`_



Packages
^^^^^^^^^

The R ecosystem relies on high quality packages and its community of package developers. Here are some
collections of package descriptions and links. 

* `RStartHere`_- A very comprehensive and well organized list of packages for doing data science in R.
* `Awesome R`_- Curated list of R packages by category (IDE, data manipulation, etc.)

Learning Python
----------------

Online Python tutorials, books and examples for getting started
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `Software Carpentry - Lessons`_ - Software Carpentry is one of my all time favorite resources for teaching and learning practical programming skills. This link takes you to their  list of "Lessons" (really entire mini-courses). In addition to a lesson on Python, you'll find lessons on tons of stuff that is useful for business analytics and data science. Highly, highly recommended.
* `Whirlwind Tour of Python - Jake VanderPlas`_ - Free 100 page pdf and associated Jupyter notebooks for those who want to learn Python for data science use and have some prior knowledge of programming.
* `Python for Everybody - Charles Severance`_ - This is a remixed, freely available, textbook on learning Python to do data analysis. 
* `Think Python (Downey) <https://greenteapress.com/wp/think-python-2e/>`_ - terrific book for newish Python learners
* `Automate the Boring Stuff with Python (Sweigart) <https://automatetheboringstuff.com/>`_ - another really good free online book
* `Ted Petrou's GitHub repos <https://github.com/tdpetrou>`_ - I stumbled on this via LinkedIn. I went through his Jupyter notebooks in the Learn-Pandas repo and they were outstanding. 

Blogs and listservs
^^^^^^^^^^^^^^^^^^^^

* `Practical Business Python`_ - Super relevant blog for business students learning Python.
* `Pycoders Weekly`_ - Weekly email newsletter. Always has interesting stuff and almost always something directly data science related.


Libraries
^^^^^^^^^^

* `Awesome Python`_ - A curated list of awesome Python frameworks, libraries, software and resources


Statistics
-----------------

If you are rusty on statistics, there's a really good OpenIntro Stats book available as a free online book or you can pay what you want for a paperback copy. It includes R based material.

* `OpenIntro Stats <https://www.openintro.org/book/ims/>`_

You can also find high quality `free online statistics courses through the Open Learning Initiative <https://oli.cmu.edu/>`_ as
well as places like Coursera and EdX.

`Cross Validated <https://stats.stackexchange.com/>`_ is a great Q&A forum for all things statistics. Lots of R related
content.
 

Publicly available data
-----------------------

* `DrivenData Competitions <https://www.drivendata.org/competitions/>`_ - not suggesting you compete (you can) but these are a great source of high quality datasets. You'll need to create a free account to be able to download data. I used this site as a motivation for my series of blog posts on `algal bloom detection from satellite imagery <https://bitsofanalytics.org/posts/algaebloom-part1/>`_.
* `Kaggle Datasets <https://www.kaggle.com/datasets>`_ - need to create a free Kaggle account
* `Data is Plural <https://www.data-is-plural.com/>`_ - links to many interesting datasets
* `Data.gov <https://data.gov/>`_ - US government data
* `Census.gov <https://www.census.gov/>`_ - US census data
* `Bureau of Transportation Statistics <https://www.transtats.bts.gov/Homepage.asp>`_ - tons of transportation rel
* `OpenML Datasets <https://www.openml.org/search?type=data&sort=runs&status=active>`_ - site with many ML resources
* `UCI Machine Learning Repository <https://archive.ics.uci.edu/ml/datasets.html>`_
* `cs109 Resources (2014) <http://cs109.github.io/2014/pages/resources.html>`_ - Many links to datasets (as well as links to Python and misc data science stuff)
* `https://github.com/rstudio/RStartHere#data <https://github.com/rstudio/RStartHere#data>`_ - From the RStartHere site
* `Google Public Data <https://www.google.com/publicdata/directory>`_
* `Climate Data Online <http://www.ncdc.noaa.gov/cdo-web/>`_
* `USGS <https://www.usgs.gov/>`_
* `dataportals.org <http://dataportals.org/>`_
* `Finding Data on the Internet (from Inside-R) <http://www.inside-r.org/howto/finding-data-internet>`_

Workflow and reproducible analysis
----------------------------------

* `Reproducible and Trustworthy Workflows for Data Science <https://ubc-dsci.github.io/reproducible-and-trustworthy-workflows-for-data-science/README.html>`_
* `Data Science Workflow: Overview and Challenges <http://cacm.acm.org/blogs/blog-cacm/169199-data-science-workflow-overview-and-challenges/fulltext>`_ - Blog post by Philip Guo who did his dissertation on this topic.
* `Cookiecutter Data Science <https://drivendata.github.io/cookiecutter-data-science/>`_ - "A logical, reasonably standardized, but flexible project structure for doing and sharing data science work."

.. _Analytics Magazine: http://analytics-magazine.org/
.. _Competing on Analytics: https://hbr.org/2006/01/competing-on-analytics
.. _Quick-R: http://www.statmethods.net/
.. _Cookbook for R: http://www.cookbook-r.com/
.. _R for Data Science: http://r4ds.had.co.nz/
.. _The Official R Manuals: https://cran.r-project.org/manuals.html
.. _Contributed Documentation: https://cran.r-project.org/other-docs.html
.. _Introducing R to a non-programmer in one hour: http://alyssafrazee.com/2014/01/02/introducing-R.html
.. _R-bloggers: http://www.r-bloggers.com/
.. _Webinars from R Studio: https://www.rstudio.com/resources/webinars/
.. _RStartHere: https://github.com/rstudio/RStartHere
.. _Awesome R: https://github.com/qinwf/awesome-R
.. _10 R packages I wish I knew about sooner: http://blog.yhat.com/posts/10-R-packages-I-wish-I-knew-about-earlier.html
.. _Teach yourself Shiny: https://shiny.rstudio.com/tutorial/
.. _Introducing R Shiny web apps | SNAP: https://blog.snap.uaf.edu/2013/05/20/introducing-r-shiny-web-apps/
.. _RStudio Add-ins: https://rstudio.github.io/rstudioaddins/#overview
.. _Software Carpentry - Lessons: http://software-carpentry.org/lessons/
.. _Whirlwind Tour of Python - Jake VanderPlas: https://github.com/jakevdp/WhirlwindTourOfPython
.. _Python for Everybody - Charles Severance: https://www.py4e.com/book.php
.. _Python for Everybody course: https://www.py4e.com/
.. _Awesome Python: https://github.com/vinta/awesome-python
.. _Learning Python - suggestions for business analytics students: http://hselab.org/learning-python-suggestions-and-resources-for-business-analytics-students-and-professionals.html
.. _Intro to Data Science in Python: https://www.coursera.org/learn/python-data-analysis
.. _Practical Business Python: http://pbpython.com/
.. _Pycoders Weekly: http://pycoders.com/


