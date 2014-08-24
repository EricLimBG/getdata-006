# Coursera: Data Science Specialization
--------------------------------------------------------------------------
### * Getting and Cleaning Data [getdata-006]
### * Course Project

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
1. Setup environment to ensure libraries/packages are available.
2. Cached meta data such as default directory, features & activities.
3. Define the [run_analysis] and [getDataset] functions.
4. Call the [run_analysis] function.
4.1 [run_analysis] calls the [getDataset] function to get 'train' dataset.
4.2 [run_analysis] calls the [getDataset] function to get 'test' dataset.
4.3 Merge 'train' and 'test' dataset into interim dataset.
4.4 Reshape interim dataset.
4.5 Apply mean function to each subject and activity in interim dataset.
4.6 Export interim dataset with tidy data to text file in repository.

##What does Tidy Data contains?
--------------------------------------------------------------------------
Upon successful execution, a text file with the tidy data will be generated in the "getdata-006\UCI HAR Dataset" repository.

The first two columns represent the subject and activity respectively. Each subject will have 6 rows of data representing the activities they have carried out.

Subsequent columns consist of standard deviation or mean measures. Data for these columns are the average of each measure for each activity and each subject
