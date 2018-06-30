# Getting-and-Cleaning-Data
Download and unzip the data file into your R working directory.
Download the R source code into your R working directory.
Finally, execute R source code to generate tidy data file.

Data description
The variables in the data X are sensor signals measured with waist-mounted smartphone from 30 subjects. The variable in the data Y indicates activity type the subjects performed during recording.

Code information
The code combines training dataset and test dataset, and extracts some of the variables to create another dataset with the averages of each variable .

New dataset
The new generated dataset contains variables calculated based on the mean and standard deviation. Each row of the dataset is an average of each activity type for all subjects.

Per the assignment:

Read training and test dataset into R environment. Read variable names into R envrionment. Read subject index into R environment.

Merge the training and the test sets to create one data set. Use command rbind to combine training and test set
Extract only the measurements on the mean and standard deviation for each measurement. Use grep command to get column indexes for variable name contains "mean()" or "std()"
Use descriptive activity names to name the activities in the data set Convert activity labels to characters and add a new column as factor
Appropriately label the data set with descriptive variable names. Give the selected descriptive names to variable columns
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject. Use pipeline command to create a new tidy dataset with command group_by and summarize_each in dplyr package
