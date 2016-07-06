# RepData_PeerAssessment1_final
Reproducible Research Assignment 1
### Introduction

This assignment makes use of data from a personal activity monitoring
device. This device collects data at 5 minute intervals throughout the
day. The data consists of two months of data from an anonymous
individual collected during the months of October and November, 2012 and
include the number of steps taken in 5 minute intervals each day.This
document presents the results from Project Assignment 1 in the Coursera
course Reproducible Research, written in a single R markdown document
that can be processed by knitr and transformed into an HTML file.

The data is loaded using the read.csv().It is assumed that you have already 
downloaded the activity.csv and saved it in your working directory. 

The total number of steps taken per day is calculated.A histogram of the 
total number of steps taken each day is plotted. The mean and median of
the total number of steps taken per day.

Time series plot (i.e. type = "l") of the 5-minute interval
(x-axis) and the average number of steps taken, averaged across all days
(y-axis) is drawn. Which 5-minute interval, on average across all the days in the
dataset, contains the maximum number of steps is determined by the calculation.?

There are a number of days/intervals where there are missing
values (coded as NA). The presence of missing days may introduce bias
into some calculations or summaries of the data.A report of the
total number of missing values in the dataset (i.e. the total number of
rows with NAs) is prepared. A strategy for filling in all of the missing
values in the dataset is devised. A new dataset that is equal to the
original dataset but with the missing data filled in is created.A histogram of
the total number of steps taken each day is calculated and reported the
mean and median total number of steps taken per day is found. 

It is determined that datasets from first part of calculations is not different
from the imputed values. Activity patterns of week days and weekends are compared.
