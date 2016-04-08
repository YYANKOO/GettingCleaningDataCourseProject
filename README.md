## Course Project for Getting and Cleaning Data

##### The dataset being used is: Human Activity Recognition Using Smartphones

##### CodeBook.md describes the variables and the data.

#### The R script, run_analysis.R, does the following:
* Load the activity and feature info.
* Load both the training and test datasets, and extract only the measurements on the mean and standard deviation for each measurement.
* Load the activity and subject data for each dataset, and merges those columns with the dataset.
* Merge the training and test datasets to create one data set.
* Convert the activity and subject columns into factor.
* Create a tidy dataset that consists of the average value of each variable for each subject and activity pair.

The resulting data set is written to the file tidy.txt.
