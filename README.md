coursera-cleaning-data
======================

Class project for Coursera - Getting and Cleaning Data

##Running the analysis
run_analysis.R is responsible for gathering, cleaning, and analyzing the data. It expects the data to be under ./data/UCI HAR Dataset. It depends on the ```plyr``` package. After running the analysis, a tidy dataset is written out to output.txt.

###Steps to run the analysis
  1. fork and clone this repository
  2. in the R terminal, set your current working directory to the project root
  3. ```install.packages("plyr")``` if you have not already installed ```plyr```
  4. source('./run_analysis.R')
