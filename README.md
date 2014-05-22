GettingAndCleaningDataProject
=============================

Coursera - Getting and Cleaning Data class project

## run_analysis.R

### Generate Dataset
Checkout the repo, and run the script run_analysis.R. 

`source("run_analysis.R")`

This will download the required package (plyr) and the required data from (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) and store it in a zip file called data.zip, After this a new folder will be generated (results/) containing the two datasets.

* dataset.csv - 10299 rows and 81 cols
* tidydata.csv - 180 rows and 81 cols

### Include dataset
The data is located in the results folder
`
dataset <- read.csv("results/dataset.csv")
tidydata <- read.csv("results/tidydata.csv")
