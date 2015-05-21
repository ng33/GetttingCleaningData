# GettingCleaningData

## Description

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

 You should create one R script called run_analysis.R that does the following. 

  1. Merges the training and the test sets to create one data set.
  2. Extracts only the measurements on the mean and standard deviation for each measurement. 
  3. Uses descriptive activity names to name the activities in the data set
  4. Appropriately labels the data set with descriptive variable names. 
  5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
  
## run_analysis.R description
sets up variables 

Downloads the dataset zip file to the local directory 

Uncompress the data file

Merges the training and the test sets to create one data set

Combines data table (train vs test) by rows

Extracts only the measurements on the mean and standard deviation for each measurement

Search for matches to argument mean or standard deviation (sd)  within each element of character vector

Replaces all matches of a string features ?write.

Uses descriptive activity names to name the activities in the data set:

Appropriately labels the data set with descriptive activity names:

Read activity labels

Friendly names to activities column

Combines data table by columns

Creates a 2nd, independent tidy data set with the average of each variable for each activity and each subject:

Created csv (tidy data set) in diretory

Created txt (tidy data set AVG) in diretory




