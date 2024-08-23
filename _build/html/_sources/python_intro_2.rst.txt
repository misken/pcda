*****************************************************
Functions, text files, reading data files with Python
*****************************************************

Intro and Objectives
====================

We'll do a few different things this session:

* We'll be creating and using functions in Python.
* We'll create and use list comprehensions and various string function
* Next we'll learn a bit about the structure of text files and tools for working with them
* We'll end our crash course into the basics of Python programming by building a simulation model of the famous Monty Hall 3-Door Problem.
* Finally I've included a several more advanced, OPTIONAL, activities about reading csv files, json files and even Excel files with Python. Within these topics I also touch on things like using PyCharm or Spyder for debugging, the conda package management program, and a few other more advanced things.
   
Readings
========

* WToP - pages 41-75

Downloads
=========

* `Downloads_IntroPython2.zip <https://drive.google.com/file/d/1LhePdN39711FfcLxWTInjFVbdUCr2IZ9/view?usp=sharing>`_
* `Downloads_ReadingFiles.zip <https://drive.google.com/file/d/1c-qH2_pzTDznvDo3Pcz72gOkHIGnBUAK/view?usp=sharing>`_

Fundamental Activities
================================

We'll finish our intro to basic Python programming:

* Creating and using functions
* List comprehensions
* Basic string work

Let's start with learning the very basics  of how to create Python functions, test and debug them and document them.

* `SCREENCAST: Creating Python functions getting them to work <https://youtu.be/siZ2jt9iNFA>`_ (20:00)
* `SCREENCAST: More on creating, using and documenting Python functions <https://youtu.be/fBG8-D4MqIk>`_ (19:59)

Now we are going to explore an interesting and useful feature of Python known as *list comprehensions*. 
We'll also dig a little bit deeper into string formatting for creating nice output.

* `SCREENCAST: List comprehensions and string formatting <https://youtu.be/xZqNmLVFX08>`_ (25:17)

The `string functions chapter in Whirlwind Tour of Python <https://jakevdp.github.io/WhirlwindTourOfPython/14-strings-and-regular-expressions.html>`_ covers useful string functions and string formatting in Python. The second half of the chapter covers regular expressions which we'll do in a future session.
By the way, there is yet another way to create formatted strings beyond the "old style" % operator and the ``format`` method. This newish approach is known as *f-strings*. A nice comparison of the three approaches can be found `at this blog post <https://mathspp.com/blog/pydonts/string-formatting-comparison>`_.

Finally, let's use our newfound knowledge of the basics of Python to do something kind of fun. I'm sure
many of you know about the famous Monty Hall 3-Door Problem made famous on 
`Let's Make a Deal! <http://math.ucsd.edu/~crypto/Monty/monty.html>`_ and in a Parade
Magazine column that set off a firestorm of controversy. Follow the link to play a few
rounds of the game so that you understand the rules. It's well known that the optimal
strategy in the classic version of this puzzle is to always switch. It's a counterintuitive
result and is always great fun to discuss (we play every year in my MIS 4460/5460 class). 

What we
are going to do is to build a Monty Hall 3-Door Problem simulator in Python. Our goal is to create
a program that lets us compare the strategies of always switching, always staying with the first door chosen, or
randomly switching or staying based on the flip of a fair coin (I'll leave this last strategy to the proverbial "reader" to do). This will force us to think through how
to design multiple functions that can be repeatedly used by a main calling program to run the
simulations and compile the results. I've included a skeleton Jupyter notebook with some of the 
code structure already created. Now let's work through filling in the gaps and getting this
simulation program working.

* `SCREENCAST: Simulating the Monty Hall 3-Door Problem - part 1 <https://youtu.be/czg5meD9yXs>`_ (15:37)
* `SCREENCAST: Simulating the Monty Hall 3-Door Problem - part 2 <https://youtu.be/sAXLlCwjVP0>`_ (24:39)

For the remainder of the materials in this section as well as the upcoming session on data wrangling
with regular expressions, we will be working with all kinds of text based files. Please take 
a look at the **IntroToTextFiles.pdf** document available in the **Downloads_ReadingFiles.zip** available above. Explore some of the links in that document so that you have a basic understanding of
text file formats, text encodings, and text editors.


OPTIONAL Advanced Activities
=============================

Feel free to pick and choose from the following based on your interests, needs, and time. None of them are absolutely essential
for this class, though of course, they may be quite useful to your final project or to your professional work.

All of the files associated with these activities are available in the **Downloads_ReadingFiles.zip** file.

We'll learn more about text files, using Python to read CSV, JSON and even Excel files. We'll also start to see more advanced programs and will use Spyder for program development and debugging. 

In the first two screencasts we'll use Jupyter notebooks. Then I'll introduce using Spyder for these same file reading problems. I'll focus on creating a new Project in Spyder and using the built in debugging tools.

* `SCREENCAST: Reading csv files <https://youtu.be/Q55OHMlcKDg>`_ (18:12)
* `SCREENCAST: Reading json files <https://youtu.be/dhuIGButFjY>`_ (9:08)

In addition to covering reading Excel data files into Python data structures, these next two screencasts also covers:

* the basics of Python package management using conda. It's kind of the equivalent to installing packages from CRAN in R.
* using the Spyder IDE 

* `SCREENCAST: Reading Excel files and installing conda packages <https://youtu.be/VwljmMnw0To>`_ (17:23)
* `SCREENCAST: More Excel file reading and using Spyder <https://youtu.be/VPHTygC-uMI>`_ (21:24)


Explore (OPTIONAL)
==================

* `Practical Business Python <http://pbpython.com/>`_ - very relevant blog on using Python for business analytics.
* `PyFormat - a guide to formatted printing <https://pyformat.info/>`_ - Covers both "old style" via % operator as well as "new style" via the .format() method and formatting mini-language. The official docs are a little tough to read on this topic and this site does a good job of explaining via common examples.
* `Introduction to scientific computing with Python <http://nbviewer.jupyter.org/github/jrjohansson/scientific-python-lectures/blob/master/Lecture-0-Scientific-Computing-with-Python.ipynb>`_ - Nice set of Jupyter notebooks for learning about doing sci-computing in Python
* `customizing your Bash prompt <https://www.digitalocean.com/community/tutorials/how-to-customize-your-bash-prompt-on-a-linux-vps>`_ - you spend a lot of time in the shell, might as well have a prompt that makes you happy.
* `Let's Make a Deal! <http://math.ucsd.edu/~crypto/Monty/monty.html>`_


