# Getting-and-Cleaning-Data-Project
## What we should do
You should create one R script called run_analysis.R that does the following. 
  1. Merges the training and the test sets to create one data set.
  2. Extracts only the measurements on the mean and standard deviation for each measurement. 
  3. Uses descriptive activity names to name the activities in the data set
  4. Appropriately labels the data set with descriptive variable names. 
  5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity
  and each subject.

##How it works
  1. Install the required packages and read the data into tables.
  2. Extract only the measurements on the mean and std.
  3. Set column names.
  4. Bind data for each test and train dataset.
  5. Merge test and train dataset
  6. Apply mean function using dcast
  7. write.table()
