#### DataScience Specialization  ####
All code as part of Data Science specialization Course

### Details about run_analysis.R

# string variables for file download
fileName, url, dir

## Reading data from the folder given with variable name as the file name
subject_test, subject_train, X_test, X_train, y_test, y_train, acitivity_labels, features

## Merge training and test data sets
dataSet

## Vector of only mean and std, use the vector to subset
MeanSTDOnly

## Vector of "Clean" feature names by getting rid of "()" apply to the dataSet to rename labels
CleanFeatureNames

## Group the activity column of dataSet, re-name lable of levels with activity_levels
act_group

## Tidy data to the working directory
secondDataSet



Steps involved:
 1. Merges the training and the test sets to create one data set.
 2. Extracts only the measurements on the mean and standard deviation for each measurement. 
 3. Appropriately labels the data set with descriptive activity names.
 4. Combine test ans train of Subject data and activity data.
 5. Combine subject, activity, and mean and std only data set to create final data set.
 6. Names to name the activities in the data set.
 7. Group the activity column of dataSet, re-name lable of levels with activity_levels, and apply it to dataSet.
 8. Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
 9. Melt data to tall skinny data and cast means. Finally write the tidy data to the working directory as "tidy_data.txt".
