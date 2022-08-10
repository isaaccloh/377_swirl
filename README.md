# 377_swirl
This is a swirl course for 377. [Swirl](https://swirlstats.com/) is a free package for R that helps us learn R, in R. The course that we will use is the R programming course developed for swirl by a number of authors: get more information and view the original course [here](https://github.com/swirldev/swirl_courses/tree/master/R_Programming).

## Installing and using
First, make sure that you have the free [RStudio IDE](https://www.rstudio.com/products/rstudio/download/) installed on your computer. This part is pretty self explanatory, but we'll go over it in class. Then, follow these steps:
1. To install this course, first make sure that you have the latest version of the `swirl` package installed. In the R console, type:
```r
install.packages("swirl")
```
You will only need to do this once.

2. Then, load the `swirl` package by entering:
```r
library(swirl)
```
You will need to do this every time you start a new R session and intend to use the `swirl` package.

3. Install this course from GitHub using `swirl` by typing:
```r
install_course_github("ikebf", "377_swirl")
```
into your R console (you only have to do this once).

4. To access the course and begin a lesson, type 
```r
swirl()
```
R will prompt you to enter your name by asking `What should I call you?`. *Please enter your last name and first initial* like this: `lohi`.

5. Follow the `swirl` prompts to navigate to the `377 swirl` course. You can select your lesson from the provided menu. 

## Submitting results
Part of the grade for our class will be assessed based on the completion of the `swirl` lessons. To submit your results at the completion of a lesson, follow these easy steps:
1. Once you reach the last question of the lesson, R will ask you if you want to submit a log of the lesson to Google Forms. Select `2: Yes`.
2. Your internet browser should open up to a Google form. Click *submit*---and you're done! 

## Uninstalling and reinstalling
Sometimes, I may have to make an edit to the swirl course---sorry in advance! In that case, to get the latest version of the course, you can uninstall it and reinstall it from GitHub:
```r
library(swirl)
uninstall_course("377_swirl")
install_course_github("ikebf", "377_swirl")
```
