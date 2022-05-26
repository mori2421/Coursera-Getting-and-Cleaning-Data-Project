# Coursera Getting and Cleaning Data Project
Course Final Assignment

Author: Morteza Roostaei <br />

Data Zip File Location: [UCI Machine Learning Repository](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip "Clicking will download the data")

## Goal of the Project
1. A tidy data set 
2. A link to a Github repository with your script for performing the analysis 
3. A code book that describes the variables, the data, and any transformations or work that you performed to clean up the data called CodeBook.md. You should also include a README.md in the repo with your scripts. This repo explains how all of the scripts work and how they are connected.
4. Analysis R Script

## Dataset Download
Data Zip File Location: [UCI Machine Learning Repository](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip "Clicking will download the data")

## R script
The R script is called run_analysis.R that does the following: 

1) Checks if the dataset already exists in the working directory and downloads the dataset if needed. 
2) Unzip the dataset.
3) Loads the required data, features and lebels into R.
4) Loads and then merges the training and the test sets to create one data set. Training and test sets are included in the downloaded dataset.
5) Extracts only the measurements on the mean and standard deviation for each measurement.  
6) Uses descriptive activity names to name the activities in the data set
7) Appropriately labels the data set with descriptive variable names. 
8) From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

