Here is the introduction.


  Values of Varible Activity consist of data from “Y_train.txt” and “Y_test.txt”
values of Varible Subject consist of data from “subject_train.txt” and subject_test.txt"
Values of Varibles Features consist of data from “X_train.txt” and “X_test.txt”
Names of Varibles Features come from “features.txt”
levels of Varible Activity come from “activity_labels.txt”
So Activity, Subject and Features as part of descriptive variable names for data in data frameAnd Read data from the activity files,subject files and features files into the variables.
Concatenate the data tables using rbind then merge colums to get the data frame(Data) for all data using cbind.
Subset Name of Features by measurements on the mean and standard deviation and subset the data frame(Data) by selected names of features.
Read descriptive activity names from "activity_labels.txt" and factorize variable activity in the data frame(Data) using descriptive activity names.
Variables activity and subject and names of the activities have been labelled using descriptive names.In this part, Names of Feteatures will labelled using descriptive variable names.
prefix t is replaced by time
Acc is replaced by Accelerometer
Gyro is replaced by Gyroscope
prefix f is replaced by frequency
Mag is replaced by Magnitude
BodyBody is replaced by Body
Independent tidy data set is created with the average of each variable for each activity and each subject based on the data set


