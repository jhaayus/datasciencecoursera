# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Download the dataset in the working directory
2. Loaded the activity and feature info
3. Change Character into Factor class
4. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation using gsub
5. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
6. Merges the two datasets
7. Converts the `activity` and `subject` columns into factors
8. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair. Done using melt and dcast function. 

The end result is shown in the file named `tidy.txt`.
