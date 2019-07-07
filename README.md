# GandCData

# Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course.
The R script, `run_analysis.R`, does the following:

1. Download the dataset if it is not already existing in your working directory
2. Load the activity, features 
3. Load both training and test data
4. Loads the activity and subject data followed by merging operation
5. Merges the two datasets above metioned
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the mean value of each of the variables for every subject and activity pair.

output dataset = "tidy_new.txt" file
