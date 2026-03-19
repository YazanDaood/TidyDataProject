# Code Book

This document describes the data, variables, and transformations used to create the tidy data set.

## Data Source
The data represents recordings of 30 volunteers performing activities of daily living while carrying a waist-mounted smartphone with embedded inertial sensors.

## Transformations Performed
1. Merged the training and test sets into one data frame.
2. Filtered columns to keep only Mean and Standard Deviation (STD) measurements.
3. Linked the activity IDs (1-6) to their descriptive names (e.g., WALKING).
4. Cleaned variable names (e.g., replaced 'Acc' with 'Accelerometer', removed brackets).
5. Aggregated the data by calculating the average of each variable for each subject and activity.

## Variables
- **subject**: ID of the volunteer (integer, 1 to 30).
- **activity**: Name of the activity performed (factor: WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING).
- **Measurements**: 66 numeric variables representing the average of the mean/std features. (e.g., `TimeBodyAccelerometerMeanX`, `FrequencyBodyGyroscopeSTDZ`).