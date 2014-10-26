Getting and Cleaning Data Course Project

You need to build R script called run_analysis.R that does the following activities.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Activities to be performed to complete this course project

Download the data source from the given url https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
.Unzip the file into a folder on your local drive. UCI HAR Dataset folder is created by the extract.
Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory for code execution.

Run source("run_analysis.R").

The code will generate a new file tidy_data.txt in your working directory.

run_analysis.R file will help you to install the dependencies by default. script uses reshape2 and data.table.