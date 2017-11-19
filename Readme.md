# *Getting and Cleaning Data* Coursera Project #

Date: 2017-11-17
Author: XXX XXX

This repository contains the following files:

 - Readme.md: This file, which contains a brief description of the data and how it was created.
 - run_analysis.R: The R script that was used to create the date.
 - secondTidyDataSet.txt: The file that contains the data set.

The full description of the source data set can be found at: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


##Creating the data set##

The R script performs the following steps in order to create the requested tidy data set:

 1. Downloads and unzips the source data file which can be found at: "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"
 2. Merges the tests and training data sets into one data set.
 3. Extracts only the measurements on the mean and standard deviation for each measurement.
 4. Adds descriptive activity names to name the activities in the data set.
 5. Labels the data set with descriptive variable names.
 6. Writes a new tidy data set with the average of each variable for each activity and each subject. The new data file is secondTidyDataSet.txt.

The new file were created with R version 3.4.1 (2017-06-30) -- "Single Candle" running on a Windows 7 Home premium HP Pavilion dv6-3187la entertainment PC.


