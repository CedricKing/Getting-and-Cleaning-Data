# Getting and Cleaning Data

This is for the submission of the Course Project for the "Getting and Cleaning Data" Module of the Data Science Certification by John Hopkins University.


## Project Requirement

Below are the requirements for the Project:

1. Merges the training and the test sets to create one data set
2. Extracts only the measurements on the mean and standard deviation for each measurement
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject

## How the Code works

1. Download the data files from [https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip] and save it in the same directory as the code
2. Download the ```run_analysis.R``` in the same directory as the data file
3. Source the ```run_analysis.R``` file
4. Execute ```run.analysis()```
5. The code will read all the required files, compute and generate a ```tiny_data.txt``` file and save it in the same working directory.
