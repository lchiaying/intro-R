Introduction to R -- Syllabus (Draft)
========================================================

This is an introduction to R programming, with a focus on applications in data analytics. Participants may have prior experience with working with data in other contexts, or with other kinds of programming, but may not necessarily have experience with data analytics or scientific computing.

## Course structure

The course curriculum will consist of two 2-hr classes devoted to learning the basics of R, and a couple of electives/special topics. For flexibility, the choice, order and number of special topics to cover can be up to the instructor. The initial two class can also be used as a stand-alone course.

### Basics of R
1. Introduction to R
2. Exploratory data analysis through visualization


### Special topics
* Databases
* Natural language processing
* Statistics and data analysis
* Creating R packages
* Rmarkdown
* Big data


## Course Objectives

By the end of the *Basics of R* section, students should achieve:
* proficiency in the basic functionality of R, and become comfortable with the features of RStudio
* an understanding of how to handle data using R, specifically how to formulate and answer analytical questions about the data
* knowledge of some of the most common and useful R libraries
* the ability for further independent exploration, relying on package documentation, online help and troubleshooting.


## Class summary

### Introduction to R
1. Illustrate what R can do with a motivating example
  * `Orange` data set: address simple statistical questions and visualization data.
* Introduce basic R objects and syntax
  * Data structures: lists, vectors, data frames (including factors and numeric features), etc.
  * Creating data: assignment operator, explicit definition, reading data from file/URL
  * Accessing data: subsetting operations, data.frame columns
  * Exploring data: 
        * view/summarize data using `head`, `summary`, `str`, `dim`, `length`, etc.
        * basic statistics, `mean`, `cov`, `quantile`, `table`, `unique`, etc.
        * Logical statements
        * subsetting and filtering
        * visualization using `plot`, `hist`, etc.
  * Introduce concept of objects and functions.
  * Defining functions
* Familiarize with RStudio
* Utilities: 
  * Read/write csv files, read data from URL
  * Saving and loading `.Rdata` files.
  * Data/memory management: `ls`, `rm`, `gc`
  * Writing `.R` scripts
  * OS tools
  * String manipulations
* Getting help: `?`, interpreting the documentation 
* Errors and Debugging


### Exploratory data analysis

* Manipulating data frames using `dplyr`: `filter`, `mutate`
* Explore the data:
  * Summary statistics (review)
  * Visualization using `plot`, `boxplot`, `hist`, etc.
* Dealing with `NA`s
* Fancy packages! The best thing about R is the wide range of freely available packages. 
  * `dplyr`
  * `data.table`
  * `ggplot2`
  * `maps`
  * `rgl`
  * `Matrix`
  * `parallel`
Use `install.packages("<package name>")` to install packages.  
* Visualization using `ggplot`, `ggpairs`, etc.


### Special topic: Databases

### Special topic: Natural Language Processing

### Special topic: Statistics and data analysis

### Special topic: Creating R packages

### Special topic: Rmarkdown

### Special topic: Big data


### Classroom mechanics

Lecture notes will be created using RMarkdown, and be made available to students. Students can follow the class examples and exercises by installing R and the IDE RStudio.


## References

* [http://www.ats.ucla.edu/stat/r/seminars/intro.htm](http://www.ats.ucla.edu/stat/r/seminars/intro.htm)
