*****************************************************
Text wrangling with Python
*****************************************************

Intro and Objectives
====================

Now that we've got some basic Python hacking skills and have learned a little about ingesting data files of various types, we are going to learn some more advanced data cleaning techniques using things like regular expressions (regex) and even "fuzzy matching". The days of purely analyzing numeric data are over and text mining skills are really nice to add to your toolkit. These topics will start us on that part of our journey.

   
Readings
========

* WToP - p76-91 (covers regex and preview of data science tools in Python)
* KDNuggets newsletter has a nice article on `Practical skills that practical data scientists need <http://www.kdnuggets.com/2016/05/practical-skills-practical-data-scientists-need.html>`_ (see first Comment too after the story).

Downloads and other resources
=============================

Regex
-----

* `Downloads_DataCleaning_regex.zip <https://drive.google.com/file/d/1iY_W38_8i1eeMFHsQ6GdNgNNlMLexkMC/view?usp=sharing>`_



Web based tools and tutorials
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* `RegExr <http://regexr.com/>`_ - an HTML/JS based site for creating, testing, and learning about Regular Expressions.
* `regex101 <https://regex101.com/>`_ - Another nice interactive web based tool for learning regex.
* `RegexOne <http://regexone.com/>`_ - Learn regular expressions with simple, interactive examples.
* `Regular-Expressions.info <https://www.regular-expressions.info/tutorial.html>`_ - One of my go to sites for regex for a long time now. Very complete, many examples with substantive explanations.
* `Learning to Use Regular Expressions - Gnossis.cx <http://gnosis.cx/publish/programming/regular_expressions.html>`_ - This is the site from which I first learned regular expressions. It has been around forever, is widely read, and quite good.
* `Regular Expressions - A Gentle User Guide and Tutorial <http://regexone.com/>`_ - This is a good tutorial, cleverly written, at a greater level of detail than some of the others above. It's got a browser based regex testing tool and the examples are based on matching parts of server logs which is a  relevant application for our class.
* `Regex Cheat Sheet <https://www.rexegg.com/regex-quickstart.php>`_
* `Regular Expressions: Now You Have Two Problems <http://blog.codinghorror.com/regular-expressions-now-you-have-two-problems/>`_ - Classic blog post on regex and a related famous quote about regex. Good links to some resources on the bare minimum that every analyst/coder/hacker should know about the incredible world of regular expressions.
* https://xkcd.com/208/

Books/Chapters
^^^^^^^^^^^^^^^

* `Mastering Regular Expressions <http://shop.oreilly.com/product/9780596528126.do>`_ (Friedl) - The definitive book on regex. 
* `Regular Expressions Cookbook <http://shop.oreilly.com/product/0636920023630.do>`_ (Goyvaerts & Levithan)
* Chapter 16 in *R for Everyone* covers string manipulation and shows how regex can be used in R.
* Chapter 7 in *Data Wrangling with Python* shows how regex can be used within Python.
* *Whirlwind Tour of Python* - p76-91

Activities
================================

* We will do several short exercises to learn the basics of regex

    - will use regex slides and `regexr.com <https://regexr.com/>`_ 
    - `SCREENCAST: Intro to regex <https://youtu.be/UTUCD4vFkAk>`_ (2:29)
    - `SCREENCAST: First quantifiers <https://youtu.be/ojO_3kbq_Ok>`_ (9:51)
    - `SCREENCAST: Escaping special characters <https://youtu.be/Q5XAoZTgnUA>`_ (3:43)
    - `SCREENCAST: Character classes and more quantifiers <https://youtu.be/vZ_Hgzi4lCI>`_ (13:09)
    - `SCREENCAST: Matching at end and/or beginning of line <https://youtu.be/QYeQtyaMYIo>`_ (6:15)
    - `SCREENCAST: General regex tips <https://youtu.be/kT1qJ3F63cw>`_ (4:19)

* Then we'll see how to use regex from within Python

    - **data_cleaning_regex.ipnyb**
    - `SCREENCAST: The python re module - part 1 <https://youtu.be/q1DE4KCdQaU>`_ (15:33)
    - `SCREENCAST: The python re module - part 2 <https://youtu.be/xoJzqk2jFpQ>`_ (4:29)
    - `SCREENCAST: The python re module - part 3 <https://youtu.be/9H9b9XqrcY4>`_ (17:19)
    - **process_apache_log.py**
    - `SCREENCAST: Using re in Python program to process Apache log file <https://youtu.be/I8oFENLdvQE>`_ (15:49)
    
* Brief intro to "fuzzy string matching".

    - **data_cleaning_fuzzy_string_matching.ipynb** uses `fuzzywuzzy`

* [OPTIONAL] Using VSCode to work with Jupyter notebooks

  Another way to work with Jupyter notebooks in Windows is with Microsoft's free
  IDE known as `VS Code <https://code.visualstudio.com/>`_.
  
    - `16 Reasons to Use VS Code for Developing Jupyter Notebooks <https://pbpython.com/vscode-notebooks.html>`_ - good blog post from Practical Business Python
    - `SCREENCAST: Intro to VS Code for Jupyter Notebooks <https://youtu.be/VhcBhxIrWjk>`_
    
* [OPTIONAL] More cleaning examples that you can explore on your own

    - **data_cleaning_finding_duplicates.ipynb** shows power of `set` data structure
    - **data_cleaning_headerfixing.ipynb** is a good exercise is complex looping over dictionaries and lists



Explore
=======

* `A REALLY RELEVANT post in the Practical Business Python blog <http://pbpython.com/case-studies.html>`_ - Includes slides from the authors talk entitled  “Escaping Excel Hell with Python and Pandas.”
* `The Absolute Minimum Every Software Developer Absolutely, Positively Must Know About Unicode and Character Sets (No Excuses!) <http://www.joelonsoftware.com/articles/Unicode.html>`_
* `Plain Text. Really? <https://www.youtube.com/watch?v=_mZBa3sqTrI>`_ - Fascinating take on the world of plain text. Highly recommended.
* `On data types in languages like Python <https://xkcd.com/1537/>`_

More on learning to program in Python
-------------------------------------

* `Advanced R <http://adv-r.had.co.nz/>`_ - This is Hadley Wickham's new book for those who want to really dig deep into R programming. 

* `Downloads_IntroPython3.zip <https://drive.google.com/file/d/1ZjMWaInh4LSaSQg1jvveAQAlU7yFOKCa/view?usp=sharing>`_

These are based on the Software Carpentry tutorials on programming with Python. They cover slightly more advanced topics. We won't cover them in class but are useful for going beyond basic programming.

* Error Handling - https://swcarpentry.github.io/python-novice-inflammation/09-errors.html
* Defensive programming - https://swcarpentry.github.io/python-novice-inflammation/10-defensive.html
* Debugging - https://swcarpentry.github.io/python-novice-inflammation/11-debugging.html
* Handling command line arguments - https://swcarpentry.github.io/python-novice-inflammation/12-cmdline.html

