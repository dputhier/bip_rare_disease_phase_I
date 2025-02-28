# BIP (Blended Intensive Programs) : "Rare Diseases at the Omics era: Current tools for frequent challenges" (Phase I remote)
  
## Objectives 

The objective of Phase I is to build a strong foundation in R programming, starting with fundamental concepts such as data structures, manipulation, and control flow. As the program progresses, learners will explore data visualization using [ggplot2](https://ggplot2.tidyverse.org/), mastering its advanced features to create insightful and customized visual representations. Finally, the phase will end up with some elements about object-oriented programming (OOP) in R, covering general concepts and methodologies for structuring user-defined classes.

## Learning modules

This first remote phase of the BIP is in self-paced learning mode. This means you will progress through the course at own speed and your own schedule. However, some meetings with teachers are scheduled (see below). These are not mandatory but can provide an opportunity to discuss any issues encountered. 

You should go through all the modules outlined below (links for module 11 to 18 will be provided later). Each topic is designed to enhance your understanding and practical skills, ensuring you can apply R effectively in data analysis and beyond.


| Module | Description |
|--------|------------|
| 01 - [Getting Started with R](https://denis-puthier-bip.shinyapps.io/01_preamble/) | Introduction to understanding basic R syntax. |
| 02 - [Working with Vectors](https://denis-puthier-bip.shinyapps.io/02_vectors/) | Understanding vectors, R’s primary data structure, and performing basic operations. |
| 03 - [Indexing and Subsetting Vectors](https://denis-puthier-bip.shinyapps.io/03_vector_indexing/) | Learn how to access, filter, and manipulate vector elements efficiently. |
| 04 - [Factors and Categorical Data](https://denis-puthier-bip.shinyapps.io/04_factors/) | Handling categorical variables in R using factors, including ordering and labeling. |
| 05 - [Matrices: Working with 2D Data](https://denis-puthier-bip.shinyapps.io/05_matrices/) | Creating and manipulating matrices, performing operations, and understanding their structure. |
| 06 - [Data Frames: The Heart of R](https://denis-puthier-bip.shinyapps.io/06_dataframes/) | Introduction to data frames, R’s most widely used structure for handling data. |
| 07 - [Data Manipulation with dplyr](https://denis-puthier-bip.shinyapps.io/07_dplyr/) | Using dplyr to filter, summarize, and transform data efficiently. |
| 08 - [Lists: Flexible Data Storage](https://denis-puthier-bip.shinyapps.io/08_listss/) | Understanding lists and how they store heterogeneous data types in R. |
| 09 - [Navigating the File System]( https://denis-puthier-bip.shinyapps.io/09_file_system/) | Reading and writing files, setting working directories, and managing paths in R. |
| 10 - [Data Type Conversions](https://denis-puthier-bip.shinyapps.io/10_conversions/) | Converting between different data types (numeric, character, factor, etc.) to ensure consistency. |
| 11 - Conditional Statements in R | Using if, else, and switch statements for decision-making in your R scripts. |
| 12 - Loops and Iterations | Implementing for loops, while loops, and alternatives for iterative programming in R. |
| 13 - Data Visualization with ggplot2: Basics | Introduction to ggplot2, setting up plots, and understanding the grammar of graphics. |
| 14 - Customizing ggplot2 Visualizations | Modifying themes, axes, colors, and labels to enhance your visualizations. |
| 15 - Advanced ggplot2 Techniques | Faceting, combining multiple plots, and working with advanced aesthetics in ggplot2. |
| 16 - ggplot2: Interactive and Specialized Plots | Creating interactive and specialized plots for deeper data exploration. |
| 17 - Writing Functions in R | Creating and using functions to make your R code more modular and reusable. |
| 18 - Object-Oriented Programming in R | Introduction to OOP in R, including S3 and S4 classes for structured programming. |

## Scheduled meetings

Several meetings with teachers are planned (see below). Attendance is not mandatory, but they offer a chance to discuss any potential issues. We may discuss later of additional slots in April and on adjusting the propose dates.

| Date              | Time (CET)               |
|------------------|------------------------|
| Wed 5 March     | 6 PM CET                |
| Sat 8 March     | 9 PM CET                |
| Wed 12 March    | 6 PM CET                |
| Sat 15 March    | 9 PM CET                |
| Wed 19 March    | 6 PM CET                |
| Wed 26 March    | 6 PM CET                |

The meeting room details will be sent via email.

## Learning evaluation

Your understanding of various aspects of R programming will be assessed through an online web form. The evaluation will primarily focus on concepts covered in learning modules 01-16. The questions will test your knowledge, problem-solving skills, and ability to apply R programming techniques effectively. 

## Running the tutorials on your own machine

The pedagological material that is provided as  web pages (see "Learning modules" section) is based on the [rtrainer](https://github.com/dputhier/rtrainer) R library that we have been developing during the last years for our students. You can install and run the tutorials on your own machine (and we encourage you to do so). The procedure should be rather straightforward:

- install a recent version of R (>4.2.3) from [CRAN](https://cran.r-project.org/). 
- install a recent version of RStudio from [Posit](https://posit.co/download/rstudio-desktop/). 
- Start RStudio. In the panel named "Console", at the bottom of the graphical interface, copy and paste successively the following instructions:

  - `install.packages("devtools")`
  - `devtools::install_github("dputhier/rtrainer")`
  - `library(learnr)`
  - `learnr::available_tutorials("rtrainer")`

Look at the tutorial names and start one of them  (here "01_preamble") using: 

- learnr::run_tutorial("01_preamble", "rtrainer") 


## Questions, discussion, remarks, issues

Submit your questions, issues, or feedback by opening an issue in this github repository (GitHub account is required) at:

- [https://github.com/dputhier/rare-disease-phase-I/issues](https://github.com/dputhier/rare-disease-phase-I/issues)


