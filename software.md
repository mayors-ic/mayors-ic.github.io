---
layout: base
---

# Getting started with software

Some of the datasets provided may need specialized software to read and analyze the data.
Python and R are two very popular data analysis tools that you can use to explore the city's data
(they are also free!).
We've provided some example instructions to help you get started working with these tools below.

----------------------------------------

# Python 

Anaconda is a very popular Python bundle that includes the programming language itself, 
along with all of its most popular packages and tools.
To get started with Anaconda, [download the installer](https://anaconda.com/download)
and follow the on-screen instructions to install it.

You can open up a Jupyter Notebook 
(an interactive programming interface for Python) using the following instructions:

* **(Windows)** - Under "All programs" in the Start Menu, click the "Jupyter Notebook" entry
  under Anaconda.
* **(Linux/macOS)** - Open up a command prompt (Applications -> Utilities -> Terminal on macOS),
  type `jupyter notebook` and press `Enter`.

Your browser should open and display a page similar to the one below.
You can enter code in a cell, and press `Shift-Enter` to run the code in a cell.

A comprehensive tutorial on how to use Python for data analysis can be found at:
[https://swcarpentry.github.io/python-novice-gapminder](https://swcarpentry.github.io/python-novice-gapminder)

### Examples

[Using Python to analyze the city's data](/examples/example_analysis_python.html)

----------------------------------------

# R

R is another popular language for data analysis. 
To get starteed with R on your laptop you will want to 
download and install two pieces of software:

* R itself - The R programming language can be downloaded from [r-project.org](https://r-project.org)
* RStudio - RStudio is a development environment for R that provides a nice user interface to make coding easier. 
  You can get it from [rstudio.com](https://rstudio.com).

Once you've installed R and RStudio, open RStudio and you can get started coding!
A comprehensive tutorial on how to use R for data analysis can be found at:
[https://swcarpentry.github.io/r-novice-gapminder](https://swcarpentry.github.io/r-novice-gapminder)

### Examples

[Using R to analyze the city's data](/examples/example_analysis_r.nb.html)

----------------------------------------

## Working with GTFS transit data

The city of Kingston stores its transit data using the GTFS format.
You will need to use the appropriate 
[GTFS language bindings](https://github.com/google/gtfs-realtime-bindings) to read or load the data.

### Examples

[Using Kingston's real-time bus data in Python](/examples/gtfs-example.html)


