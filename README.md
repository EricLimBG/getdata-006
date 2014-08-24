# Coursera: Data Science Specialization
### Getting and Cleaning Data  -  Course Project
--------------------------------------------------------------------------
##README
The R script,"run_analysis.R" performs the following:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set.
4. Appropriately labels the data set with descriptive activity names.
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

##How to generate tidy data?
To generate tidy data, execute the "run_analysis.R" script using the source command. After execution, the "tidydata.txt" file will be generated into the "getdata-006\UCI HAR Dataset" repository. Progress can be monitored via the R console during execution.

##What is done during execution?
1. Setup environment to ensure libraries/packages are available.
2. Cached meta data such as default directory, features & activities.
3. Define the [run_analysis] and [getDataset] functions.
4. Call the [run_analysis] function, that performs the following:
<br>4.1.&nbsp;&nbsp;&nbsp;Calls the [getDataset] function to get 'train' dataset.
<br>4.2.&nbsp;&nbsp;&nbsp;Calls the [getDataset] function to get 'test' dataset.
<br>4.3.&nbsp;&nbsp;&nbsp;Merge 'train' and 'test' dataset into interim dataset.
<br>4.4.&nbsp;&nbsp;&nbsp;Reshape interim dataset.
<br>4.5.&nbsp;&nbsp;&nbsp;Apply mean function to each subject and activity in interim dataset.
<br>4.6.&nbsp;&nbsp;&nbsp;Export interim dataset with tidy data to text file in repository.

##What does Tidy Data contains?
Upon successful execution, a text file with the tidy data will be generated into the "getdata-006\UCI HAR Dataset" repository.

The first two columns represent the subject and activity respectively. Each subject will have 6 rows of data representing the 6 activities that they had carried out.

Subsequent columns consist of standard deviation or mean measures. Data from these columns are the average of each measure for each activity and each subject.
