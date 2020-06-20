# Getting-and-Cleaning-Data-Course-Project

**About the Data**

The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip


**The `run_analysis.R` Script**

`run_analysis` script takes the data mencioned above and does the following:

1.Download and unzip source data if it doesn't exist. 

2.Read data.

3.Merge the training and the test sets to create one data set.

4.Extract only the measurements on the mean and standard deviation for each measurement.

5.Use descriptive activity names to name the activities in the data set.

6.Label the data set with descriptive variable names.

7.Create a second, independent tidy set with the average of each variable for each activity and each subject.

8.Write the data set to the finaltidydata.txt file.
