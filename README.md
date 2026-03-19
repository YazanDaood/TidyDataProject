# Wearable Computing Data Cleaning Project

This repository contains the R script and documentation for the "Getting and Cleaning Data" course project.

## Project Goal
The purpose is to prepare a tidy data set from the "Human Activity Recognition Using Smartphones" data collected from Samsung Galaxy S accelerometers.

## Files in this Repository
- `run_analysis.R`: The R script that performs the data preparation and cleaning.
- `FinalTidyData.txt`: The final exported tidy data set.
- `CodeBook.md`: A document describing the variables, the data, and the transformations performed.
- `README.md`: This file, explaining how the project works.

## How to run the script
1. Download the data from: [UCI HAR Dataset](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip)
2. Unzip the data into your R working directory.
3. Run `source("run_analysis.R")` in RStudio.
4. The script will generate a file named `FinalTidyData.txt`.