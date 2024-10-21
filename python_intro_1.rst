***********************************
Intro to Python for data analytics
***********************************

Intro and Objectives
====================

Python is a full-featured programming language used for all kinds of things. Our focus will be on learning Python from the perspective of doing data analytics work. Python has several advantages for data science work:

* easy to learn
* tons of data science related libraries
* many Python data science tutorials
* Python, being a full featured language, is much more powerful than R for many of the data science related tasks you'll face
* it is widely used

In this first part of the intro we'll learn about fundamental Python programming concepts such as:

* Jupyter notebooks and Jupyter lab
* variables, numpy, math, peek at plotting
* looping and conditional logic
* lists and dictionaries
* reading files
* We'll start learning to use the Spyder IDE as we start to create more complex programs.

I'm assuming that if you are in this class, you have some familiarity with computer
programming. So, this is a "whirlwind" intro to Python. The syntax is really quite
easy to learn and I focus instead on some of the concepts and data structures that those of you that just
have a VBA background might not be familiar with such as lists, dictionaries, sequential
reading of files. The Jupyter notebooks upon which this session is based are for you to
use as a starting point for further exploration and learning.
   
Readings
========

* Whirlwind Tour of Python (WToP) - pages 1-40 - `available as free pdf <https://jakevdp.github.io/WhirlwindTourOfPython/>`_. You can find the associated Jupyter notebooks in theDownloads folder for this session.
    - `Whirlwind Tour of Python notebooks as Kaggle Kernels <https://www.kaggle.com/sohier/whirlwind-tour-of-python-index>`_ - JVPs WToP free book has this set of notebooks to accompany it. Kaggle has distributed them as Kernals.
    - `Jupyter notebook keyboard shortcuts cheat sheet <https://www.cheatography.com/weidadeyue/cheat-sheets/jupyter-notebook/>`_
    - `Jupyter notebook magic commands cheat sheet <https://damontallen.github.io/IPython-quick-ref-sheets/>`_
* `Enlightenment: A Programming Story Of <https://drive.google.com/file/d/1f18VShz5FIuPX5hsJOqwL1CBQDF2o9Cp/view?usp=sharing>`_


StackOverflow is THE number one Q&A site for all things programming. There are tags for every conceivable programming language. It is essential that you learn how to ask good questions on sites like this or when asking questions of me or in our Help Forum.

* `How to ask a question on StackOverflow <https://stackoverflow.com/help/how-to-ask>`_

* `An xkcd comic on error messages in programs <https://xkcd.com/2200>`_. Remember to do the mouse-over after reading the main comic.


Downloads
=========

Inside the Download file, in addition to the files needed for this session,
you'll also find a folder with all of the Jupyter notebooks for the
Whirlwind Tour of Python book listed above.

* `Download_IntroPythonBasics.zip <https://drive.google.com/file/d/1dyiE2_jZTw9eKsbrmXtBO-4PzEgfhl1h/view?usp=sharing>`_

Activities
================================

.. note::

    Using Jupyter notebooks with conda virtual environments
    is an evolving thing. As of now (Fall 2024), and described at `this part of our software page <https://pcda.misken.org/pcda_vm#anaconda-python-distro>`_, I am using a dedicated conda virtual env named ``jupyter`` for launching Jupyter Lab.
    
        $ conda activate jupyter
        
        $ jupyter lab
        
    Then, within Jupyter Lab, I'm changing the notebook kernel to our ``datasci`` conda virtual env.
    
    But, as described at the link above, if you end up launching Jupyter Lab from the base conda env, you'll
    be fine.
     

We will begin with an overview of Python and its use in data analytics.
Then we'll start to learn Python in the context of data analysis,
by working through a number of Jupyter notebooks together. While working through the
notebooks, the topic of Conda virtual environments will come up. Conda is the `package and environment management system <https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/data-science.html>`_ for the
Anaconda Python distro. Here is a `nice newbie intro to Conda virtual environments <https://towardsdatascience.com/getting-started-with-python-environments-using-conda-32e9f2779307>`_.

If you end up using Anaconda from Windows or Mac,
eventually you'll learn about creating virtual environments (see the pcda VM page). Until then,
things will work just fine in the base environment. You may have to install
a few libraries but that's no big deal.

* **Intro to Python**

    - see the ``intro_to_python_for_business_analytics.html`` file in the Downloads folder
    - `SCREENCAST: Intro to Python <https://youtu.be/qCbtsgOFM28>`_ (23:47)
    
* **jupyter notebook vs jupyter lab**

    - we will be using JupyterLab which is the latest evolution in the Jupyter Notebook ecosystem
    - here's a `nice overview post <https://towardsdatascience.com/jupyter-lab-evolution-of-the-jupyter-notebook-5297cacde6b>`_ about this evolution
    - it is important to note that the underlying Jupyter notebooks themselves have not changed. What has changed is the interface for working with them.
    - `SCREENCAST: The relationship between Jupyter Lab and Jupyter Notebook <https://youtu.be/f8dvK1wlD0Y>`_ (9:24)
    
* **01-basics-lookahead-pcda.ipynb**

    - variables, numpy, math, peek at plotting
    - `SCREENCAST: Python basics - variables <https://youtu.be/1kFKp0JZJxc>`_ (20:36)
    - `SCREENCAST: Python basics - reading csv <https://youtu.be/eH1Ifu34OBw>`_ (16:54)
    - `SCREENCAST: Python basics - plotting <https://youtu.be/n_YXCgnVokk>`_ (7:00)
  
* **02-loop-conditionals-pcda.ipynb**

    - repeating actions
    - `SCREENCAST: Loops and Conditional logic <https://youtu.be/PO10AkDapzA>`_ (15:29)
    - `SCREENCAST: Intro to Spyder IDE <https://youtu.be/IOSroIdXqAo>`_ (7:01)
    
* **03-lists-pcda.ipynb**

    - flexible data storage, indexing and slicing
    - `SCREENCAST: Lists <https://youtu.be/k5iFZSuc_WU>`_ (10:11)

* **04-intro-dictionaries-readingfiles-pcda.ipynb**

    - another storage container, more on reading data files
    - `SCREENCAST: Dictionaries <https://youtu.be/7d-9o1HKgx0>`_ (8:40)
    - `SCREENCAST: File reading <https://youtu.be/shUp9W2agZE>`_ (17:25)
    
I didn't make screencasts for these last two. There are
very short. Just explore them.

* **05-file-globbing-pcda.ipynb**

    - processing a bunch of data files by globbing

* **06-more-on-conditions-pcda.ipynb**

    - if-then-elif-else logic

Explore
=======
* `The next billion programmers <https://benn.substack.com/p/the-next-billion-programmers>`_ - Interesting musings on Excel and Python
* `The Official Jupyter Notebook documentation <http://jupyter.readthedocs.io/en/latest//>`_
* `The MBA Data Science Toolkit: 8 resources to go from spreadsheet to command line <https://medium.com/@dmca/the-mba-data-science-toolkit-8-resources-to-go-from-the-spreadsheet-to-the-command-line-cbb59ea82144>`_ - 
* `Data Carpentry <http://www.datacarpentry.org/>`_ - Was a sibling organization to Software Carpentry, focused on helping people build better data science skills. However, recently, the two have merged and will be The Carpentries.





