# Coursera: Data Science Specialization
## [getdata-006] Getting and Cleaning Data - Course Project

##run_analysis.R
--------------------------------------------------------------------------
The R script (run_analysis.R) does the following as requested:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

##How to generate tidy data?
--------------------------------------------------------------------------
To generate tidy data, execute the "run_analysis.R" script using the source command. After execution, the "tidydata.txt" text file will be generated under the "getdata-006\UCI HAR Dataset" repository. Progress will be displayed via the R console during execution.

##What is done during execution?
--------------------------------------------------------------------------

##What does Tidy Data contains?
--------------------------------------------------------------------------
Upon successful execution, a text file with the tidy data will be generated in the "getdata-006\UCI HAR Dataset" repository. 

The first two columns represent the subject and activity respectively. 

Subsequent columns consist of standard deviation or mean measures. Data for these columns are the average of each measure for each activity and each subject
