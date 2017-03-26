# Getting-and-Cleaning-Data Project

This is the Getting and Cleaning Data Coursera course Project. The R script - run_analysis.R, does the following:

Downloads the dataset if it doesn't already exist in the WD
Load the activity and features info
Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
Loads the activity and subject data for each dataset, and merges those columns with the dataset
Merges two datasets
Converts the activity and subject columns into factors
Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file tidy.txt.
