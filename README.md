# Course Project for Coursera course "Getting and Cleaning Data"
This is a code for Course Project for Coursera course "Getting and Cleaning Data" (https://class.coursera.org/getdata-014)

It includes one R script called run_analysis.R that does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Script dowloads zipped dataset and unpack it. Script uses directory C:\GCD, if you would like to use other location--adjust line setting the working directory (line 12, setwd("C:/GCD"))

# Dataset description
Dataset provides data collected through wearable computing - see for example this article . Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Data for the project were obtained from: 
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

