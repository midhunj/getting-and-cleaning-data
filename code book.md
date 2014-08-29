# Source of data for the project:
# https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
# This R script does the following:
# 1. Merges the training and the test sets to create one data set.

Variables 

tmp1 -- holds the training dat set
tmp2-- holds the testing data set
X- binds training and testing
C- binds subject train and subject test

features 
-Uses descriptive activity names to name the activities in the data set
activities-
cleaned:
Appropriately labels the data set with descriptive activity names.

Creates a 2nd, independent tidy data set with the average of each variable for each activity and each subject.
uniqueSubjects
numSubjects 
numActivities 
numCols

write.table(result, "data_set_with_the_averages.txt") creates the final data set with averages
