# Getting and Cleaning Data

  This is a repository for any and all code written for the Course project "Getting and Cleaning Data"

# Course Project

  The goal is to prepare tidy data that can be used for later analysis
  Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

  You should create one R script called run_analysis.R that does the following. 
  0. Merges the training and the test sets to create one data set.
  0. Extracts only the measurements on the mean and standard deviation for each measurement. 
  0. Uses descriptive activity names to name the activities in the data set
  0. Appropriately labels the data set with descriptive variable names. 
  0. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# Install

  Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive)
  Put run_analysis.R into ..\UCI HAR Dataset\
  In RStudio : 
  * > setwd("..\\UCI HAR Dataset\\")
  * > source("run_analysis.R")

# Getting Result			  

  In RStudio read file "data_set_averages.txt" : 
  * > data_set_averages <- read.table("data_set_averages.txt")
  * > data_set_averages

  data_averages matrix contains 30 subjects and 6 activities

