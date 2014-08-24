# Coursera Getting and Cleaning Data

## Course Project

This repository contains my work for the course project for the Coursera course "Getting and Cleaning data" (https://class.coursera.org/getdata-006), part of the Data Science specialization. The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

##The data source

Original data: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Original description of the dataset: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones.

I refer to the README and features.txt files in the original dataset to learn more about the feature selection for this dataset.

## Create a R script called run_analysis.R that does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

## Steps to work on this course project

1. Download the data source to the UCI HAR Dataset folder.
2. Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory.
3. Run run_analysis.R to generate a new file tiny_data.txt in the working directory.

## Dependencies

run_analysis.R makes use of the library reshape2. 

## Evaluation

Sukanya Vinod· 3 days ago 
`Does that mean we have 180 rows and 80 somewhat columns? (Ex: time_Body_Accelerometer_Mean_Xaxis,time_Body_Accelerometer_Mean_Yaxis, etc along with activity and subject) in the columns?`

David Hood COMMUNITY TA· 3 days ago 
`That sounds like a tidy form (there are several, but that sounds like one of them).`

Joseph HuSignature Track· an hour ago 
`Hi, maria:
Andrew used melt() and then ddply + summarize so his results will be kept in the narrow format (4 columns.)
You used dcast() after melt() so your result will be in the wide format.
They are the same data. Just represented differently.'

https://class.coursera.org/getdata-006/forum/thread?thread_id=236
