Getting and Cleaning Data Project
======================

How the Script Works
----------------------
The run_analysis.R script contains functions that do the following behaviours:

1. Read the dataset
2. Merge the training and test datasets into one dataset
3. Extracts only the measurements on the mean and standard deviation for each measurement.
4. Uses descriptive activity names to name the activities in the data set
5. Appropriately labels the data set with descriptive activity names.
6. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

How to Run the Script
----------------------
1. extract the data first into working directory
2. run the script using -
    source('run_analysis.R')
