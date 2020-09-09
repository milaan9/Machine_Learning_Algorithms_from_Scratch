<small><small><i>
Introduction to Python - available from XXX

The original version was written by Rajath Kumar and is available at https://github.com/rajathkumarmp/Python-Lectures.

</small></small></i>

# Python-Lectures

## Introduction

Python is a modern, robust, high level programming language. It is very easy to pick up even if you are completely new to programming. 

Python, similar to other languages like matlab or R, is interpreted hence runs slowly compared to C++, Fortran or Java. However writing programs in Python is very quick. Python has a very large collection of libraries for everything from scientific computing to web services. It caters for object oriented and functional programming with module system that allows large and complex applications to be developed in Python. 

These lectures are using jupyter notebooks which mix Python code with documentation. The python notebooks can be run on a webserver or stand-alone on a computer.

To give an indication of what Python code looks like, here is a simple bit of code that defines a set $N=\{1,3,4,5,7\}$ and calculates the sum of the squared elements of this set: $$\sum_{i\in N} i^2=100$$


```python
N={1,3,4,5,7}
print('The sum of ∑_i∈N i*i =',sum( i**2 for i in N ) )
```

    The sum of ∑_i∈N i*i = 100


## Contents

This course is broken up into a number of notebooks (chapters).

* [00](Intro-to-Python/00.ipynb) This introduction with additional information below on how to get started in running python
* [01](Intro-to-Python/01.ipynb) Basic data types and operations (numbers, strings) 
* [02](Intro-to-Python/02.ipynb) String manipulation 
* [03](Intro-to-Python/03.ipynb) Data structures: Lists and Tuples
* [04](Intro-to-Python/04.ipynb) Data structures (continued): dictionaries
* [05](Intro-to-Python/05.ipynb) Control statements: if, for, while, try statements
* [06](Intro-to-Python/06.ipynb) Functions
* [07](Intro-to-Python/07.ipynb) Classes and basic object oriented programming
* [08](Intro-to-Python/08.ipynb) Scipy: libraries for arrays (matrices) and plotting
* [09](Intro-to-Python/09.ipynb) Mixed Integer Linear Programming using the mymip library
* [10](Intro-to-Python/10.ipynb) Networks and graphs under python - a very brief introduction
* [11](Intro-to-Python/11.ipynb) Using the numba library for fast numerical computing.
    

This is a tutorial style introduction to Python. For a quick reminder / summary of Python syntax the following [Quick Reference Card](http://www.cs.put.poznan.pl/csobaniec/software/python/py-qrc.html) may be useful. A longer and more detailed tutorial style introduction to python is available from the python site at: https://docs.python.org/3/tutorial/


## Installation

* Press the start button (if prompted by the system)
* Use the menu of the jupyter system to upload a .ipynb python notebook file or to start a new notebook.

### Installing 

Python runs on windows, linux, mac and other environments. There are many python distributions available. However the recommended way to install python under Microsoft Windows or Linux is to use the Anaconda distribution available at [https://www.continuum.io/downloads]. Make sure to get the Python *3.5* version, not 2.7. This distribution comes with the [SciPy](https://www.scipy.org/) collection of scientific python tools as well as the iron python notebook. For developing python code without notebooks consider using [spyder](https://github.com/spyder-ide/spyder) (also included with Anaconda)

To open a notebook with anaconda installed, from the terminal run:

    ipython notebook

Note that for the Monash University optimisation course additional modules relating to the commercial optimisation library [CPLEX](http://www-01.ibm.com/software/commerce/optimization/cplex-optimizer/index.html) and possibly [Gurobi](http://www.gurobi.com/) may be used. These libraries are not available as part of any standard distribution but are available under academic licence and are included on the [Monash server](https://sci-web17-v01.ocio.monash.edu.au/hub).

## How to learn from this resource?

Download all the  notebooks from [XXX]

Launch ipython notebook from the folder which contains the notebooks. Open each one of them

Cell > All Output > Clear

This will clear all the outputs and now you can understand each statement and learn interactively.


## License
This work is licensed under the Creative Commons Attribution 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by/3.0/
