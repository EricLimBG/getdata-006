# Coursera: Data Science Specialization
### Getting and Cleaning Data  -  Course Project
--------------------------------------------------------------------------
##CODE BOOK


###Environment Variables & Meta Data
* dataDir - a character containing directory where the data files reside.
* activities - a factor containing the activities performed when measures were taken.
* features - a factor containing the measures taken. features.std and features.mean are logical variables used to extract measures from dataset.

###Functions, Variables & Datasets
1. getDataSet(set=character) - a function used to read feature, activity & suject data from files. 'set' determines to read from train or test data. The function returns a factor dataset.
<br>1.1.&nbsp;&nbsp;&nbsp;Variables 
<br>1.1.1.&nbsp;&nbsp;&nbsp;featureFile - a character containing the file name of feature dataset.
<br>1.1.2.&nbsp;&nbsp;&nbsp;activityFile - a character containing the file name of activity dataset.
<br>1.1.3.&nbsp;&nbsp;&nbsp;subjectFile - a character containing the file name of subject dataset.
<br>1.2.&nbsp;&nbsp;&nbsp;Datasets
<br>1.2.1.&nbsp;&nbsp;&nbsp;featureData - 
<br>1.2.2.&nbsp;&nbsp;&nbsp;activityData - 
<br>1.2.3.&nbsp;&nbsp;&nbsp;subjectData - 
2. runAnalysis - function
<br>2.1.&nbsp;&nbsp;&nbsp;Variables
<br>2.2.&nbsp;&nbsp;&nbsp;Datasets
<br>2.2.1.&nbsp;&nbsp;&nbsp;trainData - 
<br>2.2.2.&nbsp;&nbsp;&nbsp;testData - 
<br>2.2.3.&nbsp;&nbsp;&nbsp;mergedData - 
<br>2.2.4.&nbsp;&nbsp;&nbsp;meltData - 
<br>2.2.5.&nbsp;&nbsp;&nbsp;tidyData - 

###Transformation
