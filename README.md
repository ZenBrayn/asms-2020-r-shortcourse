# ASMS Reboot 2020 Short Course: Getting Started with R for Mass Spectrometry Data Analysis

## Course Logistics

**Date**: Wednesday, June 17, 2020 (one-day course)

**Time**: 9AM -- 4PM CDT (7AM -- 2PM PDT, 10AM -- 5PM EDT)

**Location**: Online (Zoom link TBD)

## Course Description

This course is designed to help participants develop a solid foundation in the basics of the R programming language and understand how it can be used to perform the types of data analysis tasks scientists frequently encounter in their daily work. While the focus of the course will be on learning practical fundamentals of R for data analysis in general, mass spectrometry specific examples will be used during the course, making it well suited for ASMS members interested in adding data analysis skills to their scientific toolbelt. The main goal of the course is to help scientists, who are new to R and perhaps coding in general, get to the point where they can begin to perform basic data analysis tasks and produce data visualizations on their own, as well as to provide the basis for further study on the road to R fluency.

The course will focus on three main topics:

1. **Introduction to R and RStudio**: A high-level and practical introduction to R, covering the essential fundamentals that
one needs to start doing basic data analysis tasks.
2. **Working with tidy Data**: An introduction to the `tidyverse` ecosystem of R packages and how they can be used
to facilitate efficient and organized data analyses.
3. **Visualization with ggplot2**: An introduction to the `ggplot2` data visualization package, with an emphasis on
practical fundamentals, so participants can start making basic plots and visualizations from their own data.

Please note that this course will not focus on the details of specific analysis and statistical methods, and how they can be applied to mass spectrometry data. Rather, the focus of the course is on helping new R users learn the essential fundamentals so they can start using R in their daily work. While one cannot expect to master R in one day, this course will help participants get over some of the initial hurdles that new R users often face. Additional learning resources and recommendations will also be provided at the end of the course to help participants continue their study of R.

## Prerequisites

All participants will need a laptop in order to view the online course and perform the example exercises. Instructions will be provided in advance on any required software and set-up needed.

Participants should have some experience performing basic data analysis tasks, for example, using Excel and/or MS vendor software to process and review data.

While previous programming experience can be useful for learning R, it is not specifically required for this course since the focus will be on the use of R for data analysis as opposed to teaching participants how to program specifically. Those new to R, and programming in general, are welcome!

## Instructors

**Ryan Benz**, Seer, Inc.

**Jeffrey Jones**, SoCal Bioinformatics

**N. Heath Patterson**, Vanderbilt School of Medicine

## Course Schedule

*IMPORTANT: ALL TIMES LISTED BELOW ARE CENTRAL DAYLIGHT TIME (CDT)*

| Time | Duration  | Session |
| ---  | ---       | ---     |
| 9:00 -- 9:15 AM  | 15 min | Course introduction |
| 9:15 -- 9:45 AM  | 30 min | First steps with R and RStudio |
| 9:45 -- 10:00 AM | 15 min | Practice session #1 |
| 10:00 -- 10:30 AM| 30 min | R data structures: vectors & data frames |
| 10:30 -- 10:45 AM| 15 min | *Break* |
| 10:45 -- 11:00 AM| 15 min | Practice session #2 |
| 11:00 -- 11:30 AM| 30 min | Useful R functions |
| 11:30 -- 11:45 AM| 15 min | Practice session #3 |
| 11:45 -- 12:00 AM| 15 min | Morning wrap-up & questions |
| 12:00 -- 1:00 PM | 1 hr | *Lunch* |
| 1:00 -- 1:30 PM | 30 min | Introduction to tidy data and the `tidyverse` |
| 1:30 -- 1:45 PM | 15 min | Practice session #4 |
| 1:45 -- 2:15 PM | 30 min | Example data pipelines with `dplyr` |
| 2:15 -- 2:30 PM | 15 min | Practice session #5 |
| 2:30 -- 2:45 PM | 15 min | *Break* |
| 2:45 -- 2:50 PM | 5 min  | Introduction to data visualization | 
| 2:50 -- 3:15 PM | 25 min | `ggplot2` basic syntax |
| 3:15 -- 3:45 PM | 30 min | Practice session #6 |
| 3:45 -- 4:00 PM | 15 min | Break |
| 4:00 -- 4:10 PM | 10 min | `ggplot2` extended syntax |
| 4:10 -- 4:30 PM | 20 min | Practice session #7 & #8 |
| 4:30 -- 4:45 PM | 15 min | Course wrap-up, review, next steps |


## Pre-Course Preparation

This course is meant to provide both lecture style instruction and hands-on practice working with R.  As such, participants will need to complete some pre-course preparations so they are ready to participate during the short course instruction.

1. Download the course materials from the GitHub repository.
    * **If you are familiar with Git**, clone the repository to your personal computer
    * **If you don't know about Git**, you can download the files as a .zip file.  Look for the green "Clone or download" button near the top of the main course page on GitHub, and click "Download ZIP".  Unzip the file on your personal computer.
2. If you need help installing R and RStudio, see the [provided installation notes](https://github.com/ZenBrayn/asms-2020-r-shortcourse/blob/master/presentations/00_installing_r_and_rstudio.pdf).
3. Take a quick look through the structure of the downloaded files and directories.  We will be using these materials during the course, e.g. working with the provided R scripts.

Given the current situation with COVID-19 that has necessitated the move of the course to an online format, there are two ways that participants can work with R and the materials during the course:

1. **Install R and Rstudio on your personal computer**.  Please see the [installation notes](https://github.com/ZenBrayn/asms-2020-r-shortcourse/blob/master/presentations/00_installing_r_and_rstudio.pdf) for more information.  If you chose this option, you will need to download the course materials from the GitHub repository and follow along with the provided R scripts during the course.
2. **Utilize Rstudio Cloud**.  We will also be using a cloud-based environment that participants can use to access R, Rstudio and the example R scripts.  *This is not required*, but can simplify the process because it provides a "ready to go" instance of Rstudio and the example files all from your web browser.  If you chose this option, you don't need to install R or Rstudio on your personal computer, but you will need to make an account with Rstudio Cloud and join the course workspace.  A link to join the Rstudio Cloud workspace will be provided in a separate email from ASMS.

If using option 1 above, you will need to install a few R packages before the course.  You can do this within RStudio:

1. Open RStudio
2. Select "Tools --> Install Packages"
3. In the "Packages" field, enter the name of the package (provided below)
4. Click "Install"

These are the names of the packages you need to install (please type exactly as shown below):

* `tidyverse`





