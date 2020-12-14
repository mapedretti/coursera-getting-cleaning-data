# Dtails of run_analysis.R script

This is the script used to perform analysis on raw data to create a tidy datafile called avgSujectActivities.txt


# Original Data Source

Data for analysis is downloaded from the below URL
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip


# Functions of run_analysis.R Script

1. Downloads the dataset from the URL mentioned above and unzips it to create UCI HAR Dataset folder
2. Imports test and train datsets and creates data frames from then and then Merges the training and the test sets to create one data frame.
3. Extracts a subset of data with only the measurements on the mean mean() and standard deviation std() for each measurement. 
4. Appropriately labels the data set with descriptive activity names in place of activity Ids
5. Reshapes dataset to create a data frame with average of each measurement variable for each activity and each subject
6. Writes new tidy data frame to a text file to create the required tidy data set file 


# Running the script

To run the script, you just have to download the script and source the script from your working directory in R. source(run_analysis.R)
