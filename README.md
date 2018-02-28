
Getting and Cleaning Data Course Project

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The dataset is downloaded if not present.
Raw data are read from eight files the dataset. 
The raw data are merged into a single table for which:
Each row represents a set of measurements on observations of accelerometer and gyroscope data collected by a smartphone worn by a particular volunteer performing a particular activity. More on subjects, activities, and measurements below.

The columns represent:
The subject's ID.
The subject's activity.

A set of 561 measurements computed from accelerometer/gyroscope readings.

66 of the 561 measurement types are extracted, consisting of means and standard deviations. The rest are discarded.

The 66 mean and standard-deviation measurement types are summarized as follows:

For each combination of subject, activity, and measurement type, all corresponding measurements are averaged.

A summary table is prepared, with:
A row for each combination of subject and activity.
One column of subject IDs.
One column of activity names.
66 columns, for each of the measurement types.
The summary table is written in tabular form to uci_har_dataset_summary.txt.
