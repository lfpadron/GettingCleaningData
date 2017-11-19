# Code book for Coursera *Getting and Cleaning Data* course project

The data set that this code book pertains to is located in the `secondTidyDataSet.txt` file of this repository.

See the `README.md` file of this repository for background information on this data set.


## Data <a name="data"></a>

The `secondTidyDataSet.txt` data file is a text file, containing space-separated values.

The first row contains the names of the variables,  and the following rows contain the values of these variables. 


## Transformations <a name="transformations"></a>

The zip file containing the source data is located at [https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip).

The following transformations were applied to the source data:

1. The training and test sets were merged to create one data set.
1. The measurements on the mean and standard deviation (i.e. signals containing the strings `mean` and `std`) were extracted for each measurement, and the others were discarded.
1. From the data set in step 2, the final data set was created with the average of each variable for each activity and each subject.

The collection of the source data and the transformations listed above were implemented by the `run_analysis.R` R script (see `README.md` file for usage instructions). 