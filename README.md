# TidyDataset
# Getting and Cleaning Data - Course Project

## Overview

This repository contains the R script `run_analysis.R`, which processes the Human Activity Recognition Using Smartphones Dataset to create a tidy dataset that contains the average of each measurement for each activity and each subject.

The goal is to demonstrate the ability to clean and prepare data for analysis following the principles of tidy data.

---

## Files Included

- `run_analysis.R`: The R script that performs all the steps required by the project.
- `tidy_dataset.txt`: The final tidy data output.
- `README.md`: This file explaining the project.
- `CodeBook.md`: [You should create this separately — explains variables and transformations.]

---

## Steps Performed in `run_analysis.R`

1. **Merges the training and the test sets** to create one data set.
2. **Extracts only** the measurements on the mean and standard deviation for each measurement.
3. **Uses descriptive activity names** to name the activities in the data set.
4. **Labels the data set with descriptive variable names.**
5. **Creates a second tidy data set** with the average of each variable for each activity and each subject.

---

## How to Run

1. Download and unzip the dataset:  
   [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)

2. Set the working directory in R to the folder containing the extracted data:
