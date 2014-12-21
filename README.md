
GettingAndCleaningData_CourseProject
====================================
## Create one R script called run_analysis.R that does the following:
## 1. Merges the training and the test sets to create one data set.
## 2. Extracts only the measurements on the mean and standard deviation for each measurement.
## 3. Uses descriptive activity names to name the activities in the data set
## 4. Appropriately labels the data set with descriptive activity names.
## 5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## First, load in activity_labels.txt and fetaures.txt for R can read in table labels
## Then, extract the mean and std dev measurements from both test (X_test.txt, y_test.txt and subject_test.txt) and train (X_train.txt, y_train.txt and subject_train.txt) data, while loading in the label names
## Next, merge the two datasets together, with the correct labels
## Finally, produce tidy data set with proper labels for both the test and train data "tidy_data.txt"
