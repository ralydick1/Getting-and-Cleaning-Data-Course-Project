# Getting-and-Cleaning-Data-Course-Project

This is a repo containing code to complete the course Poject for the Getting and Cleaning Data week 4 project. To use please:
* Download the R source code into your R working directory.
* Execute R source code to download and generate tidy data file.

### Data description
The data here issensor signals measured with waist-mounted smartphone from 30 subjects. The variable in the data indicates activity type that the subjects performed during collection. A full description of the data can be found within the downloaded Zip file entitiled "Readme.txt"

### Code explaination
The code combines training data with test data of the afforementioned signal data based on type of activity peformed during the data collection process. It then extracts variables to create an output of averages for each variable for each activity.

### New dataset
The new generated dataset is mean and standard deviations of the values from collection. Each row of the dataset is an average of each activity type for all subjects.

### The code was written based on the instruction of this assignment
The code should:
1. Merges the training and the test sets to create one data set.
Use command rbind to combine training and test set
2. Extracts only the measurements on the mean and standard deviation for each measurement.
Use grep command to get column indexes for variable name contains "mean()" or "std()"
3. Uses descriptive activity names to name the activities in the data set
Convert activity labels to characters and add a new column as factor
4. Appropriately labels the data set with descriptive variable names.
Give the selected descriptive names to variable columns
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
