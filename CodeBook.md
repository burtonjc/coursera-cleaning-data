CodeBook
========
All of the analysis takes place in [run_analysis.R](https://github.com/burtonjc/coursera-cleaning-data/blob/master/run_analysis.R). Running that one file will clean up the data into a single tidy data set and run a small bit of analysis on it.

##Variables
After running the analysis, you will see a variable called ```data``` in your environment. ```data``` contains a data frame of the tidied data that the analysis will be run on.

##Data
The original data lives under ```./data/UCI HAR Dataset/```. The data is split between two groups called test and train. run_analysis cleans this data into the ```data``` variable. The first column in ```data``` is the subject id, the second is the activity, and the rest are measurments around mean and standard deviation.

##Transformations
The following transormations take place in [run_analysis.R](https://github.com/burtonjc/coursera-cleaning-data/blob/master/run_analysis.R):
  1. 
