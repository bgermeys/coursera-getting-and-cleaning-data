# Coursera Getting and Cleaning Data

## Course Project

This repository contains my work for the course project for the Coursera course "Getting and Cleaning data" (https://class.coursera.org/getdata-006), part of the Data Science specialization. The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

##The data source

Original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Original description of the dataset: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
I refer to the README and features.txt files in the original dataset to learn more about the feature selection for this dataset.

## Create an R script called run_analysis.R that does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

## Steps to work on this course project

1. Download the data source and put into a folder on your local drive, the ```UCI HAR Dataset``` folder.
2. Put ```run_analysis.R``` in the parent folder of ```UCI HAR Dataset```, then set it as your working directory using ```setwd()``` function.
3. Run ```"run_analysis.R"``` to generate a new file ```tiny_data.txt``` in your working directory.

## Dependencies

```run_analysis.R``` depends on the libraries ```reshape2``` and ```data.table```. 

