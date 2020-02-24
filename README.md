# Darden_IntroToPython
Introduction to Python session for UVA's Darden Business School

## Who am I?
* Erich Purpur
* Research Librarian for Science & Engineering

I'm a part of a group called [research data services](https://data.library.virginia.edu/) and I do these things:
    
    1. Serve as Liaison to various engineering departments
    2. Teach workshops and classes (like this one)
    3. Help people with research projects
    4. Random other things as they come up
    
    * ep9k@virginia.edu 
    * Brown Science & Engineering Library office i046
    
* I like to be interrupted with questions! Please jump right in. 

## Getting Python (this will take about 10 minutes)
* [Windows](https://www.anaconda.com/download/#windows)
* [Mac](https://www.anaconda.com/download/#macos)

## Getting the files we are working with today
* Click "Clone or Download" (green button in upper right corner)
* Click "Download Zip"
* Unzip that directory and move it somewhere that is easy to find (like your Desktop, for example)

# Goals for Today
1. Get python running
2. Learn some fundamentals
3. Play with some data
4. Learn how to help yourself (Most Important!)
5. Think about...Why would this help me as a manager or in a business context?


# What is Python?
From [www.python.org](http://www.python.org):
"Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in 
data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, 
as well as for use as a scripting or glue language to connect existing components together. Python's simple, easy to learn 
syntax emphasizes readability and therefore reduces the cost of program maintenance." 

Python is a general purpose programming language used for a huge variety of purposes. It's user community is growing rapidly!
(https://stackoverflow.blog/2017/09/06/incredible-growth-python/)

# Object Oriented Programming (Very Brief Overview)
I mentioned that python is an Object Oriented Language. What does that mean?

Object oriented languages (Python, Java, C++ for example) use objects which contain data in the form of fields, and code in 
the form of procedures. In object oriented programming, computer programs are designed by making them out of objects that 
interace with one another. Python is a class-based language, meaning objects are an instance of a class.

# Why learn Python instead of other languages?
* Python is not magic. Many other languages can do what python does.
* Python is widely used and has a ton of available resources
* Python is easy to learn
* Python is general purpose (you can do a lot of different things with it)

# What are the drawbacks of Python?
* Keep in mind python does have drawbacks!
    - Speed
    - Mobile application development
* Python is general purpose (it is not optimized for performance in one specific area)
    - Python is like a Honda CR-V (I drive a CR-V). It does it all. 
        - If you are a construction worker, you need a truck to haul tools and materials
        - If you are a race car driver, you need a sports car
    
    
# Difference between R and Python?  (Simplified)
* They are both open source programming languages
* Python is general purpose while R is focused on statistics and data analysis
* You can also do stats with Python. Many packages available
    * NumPy
    * SciPy
    * Pandas
    
    
# Why should I care as a business person?
Even if you don't intend to become a pro yourself, if you think you might be working with or managing developers, it can be 
really beneficial to at least have some working knowledge of what they do. Knowing just a little bit can go a long way!
    
A complaint heard from developers or other technical people is: "My manager is asking me to do something impossible because 
he/she doesn't understand how the code works!". Don't be that manager. 

# Important Points about Programming to Grasp
These are not specific to python

Programming allows us to...
- Interact with computers!
    - Who doesn't use a computer these days?
- Automate things (perform repetitive tasks)
    - Computers don't get bored
    - Computers don't make mistakes (humans who create them make mistakes)
- Analyze huge data sets 

When learning to program you will...
- Develop critical thinking skills
    - How do I attack the problem?
- Be forced develop a clear line of thought
    - The code only does what you tell it to do
    - If you are confused, the computer is confused
- Constantly adapt and learn
    - Programming languages are alive and always changing!

# Python is an Embedded Language
Because python is a popular language, it is sometimes embedded inside another programs so that you can natively code in 
python to make that program do things. This allows you to implement the functionality of that program in python instead of C 
or C++ (which is probably running behind python). Often there is a terminal-like window or IDE embedded within the program. 
This is hugely useful for automating tasks, creating custom functionality, etc. 

Example:
    - python module in Tableau
    - python module in nearly all GIS softwares including ArcGIS and QGIS

# Let's Get Coding in Python

## **Jupyter Notebook/JupyterLab**
*[Jupyter Homepage](https://jupyter.org/)*

Another topic to cover is Jupyter Notebooks and/or JupyterLab. 
Jupyter Notebooks are a web-based interactive computational environment for creating notebook-like documents. It supports 
several languages like python, R, Julia, etc.
JupyterLab is the next generation user interface, which includes Jupyter Notebooks. 

In my opinion, they seem almost exactly the same. We will be using Jupyter Notebooks today.


## **Pandas**
*[Pandas Homepage](https://pandas.pydata.org/)*

Pandas is an open source python library providing high-performance, easy-to-use data structures and data analysis tools. We 
will be using pandas to work with our data before feeding it into matplotlib.

Pandas allows you a spreadsheet-like view of your data.


## **Matplotlib**
*Excerpt taken from [MatPlotLib's Website](https://matplotlib.org/):*

Matplotlib is a Python 2D plotting library which produces publication quality figures in a variety of hardcopy formats and 
interactive environments across platforms. Matplotlib can be used in Python scripts, the Python and IPython shells, the 
Jupyter notebook, web application servers, and four graphical user interface toolkits.

Matplotlib tries to make easy things easy and hard things possible. You can generate plots, histograms, power spectra, bar 
charts, errorcharts, scatterplots, etc., with just a few lines of code.

*From [MatPlotLib's Wikipedia page](https://en.wikipedia.org/wiki/Matplotlib):*
Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It 
provides an object-oriented API for embedding plots into applications



# **Self Help - You don't need to remember all of this**

# Learning Resources - My other workshops
* [Intro to Python (more in depth Introduction)](https://github.com/epurpur/python-intro)
* [Python and APIs](https://github.com/epurpur/pythonAPI)
* [Python Data Visualization (MatPlotLib)](https://github.com/epurpur/PythonDataViz)
* [Python Web Scraping](https://github.com/epurpur/PythonWebScraping)



# More Resources
* Pick up a book, there are many available through the UVA library website 
        * Learn Python the Hard Way (Available for free through UVA libraries)
        * [Link here](https://search.lib.virginia.edu/catalog/u7434195)
        
* CS 1110/1111 @ UVA
        * All resources available online for free!
        * https://cs1110.cs.virginia.edu/
        
* Phd+ Course Materials
        * All resources available online for free!
        * https://workshops.rc.virginia.edu/lesson/python_shortcourse/python_introduction

* Other resources available at UVA
        * Research Data Services - StatLab Fellows
        * https://data.library.virginia.edu/statlab/
        * statlab@virginia.edu
        * Research Computing - Provides high performance computing expertise
            * https://www.rc.virginia.edu/

# Self Help via the Internet
  * Google 
        * Ex: "How to make dictionary python"
        * Ex: "python decorators"
        
  * Stack Overflow (https://stackoverflow.com/)
        * A question/answer site for programming questions (actually, not just programming any more)
        * Not only python
        * DO NOT just ask questions, do your research first!
            * Odds are very high someone has already asked your question, especially as a novice
     
  * Youtube
        - Corey Schafer (https://www.youtube.com/channel/UCCezIgC97PvUuR4_gbFUs5g)
            - If you have a question about a python programming concept, Corey Schafer has covered it
     
  * Practice Python (http://www.practicepython.org/)
        * Coding challenges for programmers of all levels
        
  * Python Tutor (http://pythontutor.com/)
        * Visualize what your code is doing step-by-step
        * Has limitations once you start importing libraries
        
  * TalkPython Training (https://training.talkpython.fm/)
        * Not free
        * Really awesome courses that help you get "real world" project experience
