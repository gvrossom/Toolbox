## Getting and Cleaning Data Project - Hello peers!

This repo contains a script run_analysis.R containing two functions 
designed to fullfil the project assignement of Getting and Cleaning data

First of all, you have to donwload the Samsung data, you can do it manually or by using the donwload.file() and unzip() functions.
Secondly, the data.table package is requried for the second function to run.

the first function loads the needed data sets and processes as follow:
  1) Construct the relative pathes of data files
  2) Read the data into a data.frame and then turns it into data.table

The second function run.analysis() performs the following job:
  It Merges the training and the test sets to create one data set.
  Extracts only the measurements on the mean and standard deviation for each measurement. 
  Uses descriptive activity names to name the activities in the data set and then
  appropriately labels the data set with descriptive variable names.
  
  The function processes as follow:
 <li> Get the features and labels
 <li> Read train and test data sets
 <li> Generate the tidy data set
 <li> Writte the appropriate variable names
  
  Finally, it creates an independent tidy data set with the average of each variable for each activity and each subject.
