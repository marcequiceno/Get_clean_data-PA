#Getting and Cleaning data Course Project. Peer Assessments
##CodeBook for Tidy Dataset

###Varibles

|Var Name|Definition|Comments/Units|
|--------|----------|--------------|
|Subject_ID|Identifier of the subject who carried out the experiment|Unique Integer| 
|Activity_Label|text labels for the above codes||
|tBodyAccmeanX|body acceleration signal obtained by subtracting the gravity from the total acceleration, mean X axis| standard gravity units “g”|
|tBodyAccmeanY|body acceleration signal obtained by subtracting the gravity from the total acceleration, mean Y axis| standard gravity units “g”|
|tBodyAccmeanZ|body acceleration signal obtained by subtracting the gravity from the total acceleration, mean Z axis| standard gravity units “g”|
|tBodyAccstdX|body acceleration signal obtained by subtracting the gravity from the total acceleration, standard deviation, X axis| standard gravity units “g”|
|tBodyAccstdY|body acceleration signal obtained by subtracting the gravity from the total acceleration, standard deviation, Y axis| standard gravity units “g”|
|tBodyAccstdZ|body acceleration signal obtained by subtracting the gravity from the total acceleration, standard deviation, Z axis| standard gravity units “g”|
tGravityAccmeanX|gravity acceleration signal obtained by subtracting the gravity from the total acceleration, mean, X axis| standard gravity units “g”|
tGravityAccmeanY|gravity acceleration signal obtained by subtracting the gravity from the total acceleration, mean, Y axis| standard gravity units “g”|
tGravityAccmeanZ|gravity acceleration signal obtained by subtracting the gravity from the total acceleration, mean, Z axis| standard gravity units “g”|
tGravityAccstdX|gravity acceleration signal obtained by subtracting the gravity from the total acceleration, standard deviation, X axis| standard gravity units “g”|
tGravityAccstdY|gravity acceleration signal obtained by subtracting the gravity from the total acceleration, standard deviation, Y axis| standard gravity units “g”|
tGravityAccstdZ|gravity acceleration signal obtained by subtracting the gravity from the total acceleration, standard deviation, Z axis| standard gravity units “g”|
tBodyAccJerkmeanX|gravity acceleration w/jerk signal obtained by subtracting the gravity from the total acceleration, mean, X axis| standard gravity units “g”|
tBodyAccJerkmeanY|gravity acceleration w/jerk signal obtained by subtracting the gravity from the total acceleration, mean, Y axis| standard gravity units “g”|
tBodyAccJerkmeanZ|gravity acceleration w/jerk signal obtained by subtracting the gravity from the total acceleration, mean, Z axis| standard gravity units “g”|
tBodyAccJerkstdX|gravity acceleration w/jerk signal obtained by subtracting the gravity from the total acceleration, standard deviation, X axis| standard gravity units “g”|
tBodyAccJerkstdY|gravity acceleration w/jerk signal obtained by subtracting the gravity from the total acceleration, standard deviation, Y axis| standard gravity units “g”|
tBodyAccJerkstdZ|gravity acceleration w/jerk signal obtained by subtracting the gravity from the total acceleration, standard deviation, Z axis| standard gravity units “g”|
tBodyGyromeanX|angular velocity vector measured by the gyroscope for each window sample, mean, X axis| units: radians/second|
tBodyGyromeanY|angular velocity vector measured by the gyroscope for each window sample, mean, Y axis| units: radians/second|
tBodyGyromeanZ|angular velocity vector measured by the gyroscope for each window sample, mean, Z axis| units: radians/second|
tBodyGyrostdX|angular velocity vector measured by the gyroscope for each window sample, standard deviation, X axis| units: radians/second|
tBodyGyrostdY|angular velocity vector measured by the gyroscope for each window sample, standard deviation, Y axis| units: radians/second|
tBodyGyrostdZ|angular velocity vector measured by the gyroscope for each window sample, standard deviation, Y axis| units: radians/second|
tBodyGyroJerkmeanX|angular velocity vector measured by the gyroscope for each window sample, with jerk, mean, X axis| units: radians/second|
tBodyGyroJerkmeanY|angular velocity vector measured by the gyroscope for each window sample, with jerk, mean, Y axis| units: radians/second|
tBodyGyroJerkmeanZ|angular velocity vector measured by the gyroscope for each window sample, with jerk, mean, Z axis| units: radians/second|
tBodyGyroJerkstdX|angular velocity vector measured by the gyroscope for each window sample, with jerk, standard deviation, X axis| units: radians/second|
tBodyGyroJerkstdY|angular velocity vector measured by the gyroscope for each window sample, with jerk, standard deviation, Y axis| units: radians/second|
tBodyGyroJerkstdZ|angular velocity vector measured by the gyroscope for each window sample, with jerk, standard deviation, Z axis| units: radians/second|


-Subject: identifier of the subject who carried out the experiment. The experiments have been carried out with a group of 30 volunteers, each person performed six activities.  
- Activity_Label: Laying, Sitting, Standing, Walking, Walking_downstairs, Walking_upstairs.  
-Average of the mean and standard deviation for: Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration (standard gravity units 'g') and Triaxial Angular velocity from the gyroscope (units randians/second). List of variables:  
tBodyAcc-mean()-X  
tBodyAcc-mean()-Y  
tBodyAcc-mean()-Z  
tBodyAcc-std()-X  
tBodyAcc-std()-Y  
tBodyAcc-std()-Z  
tGravityAcc-mean()-X  
tGravityAcc-mean()-Y  
tGravityAcc-mean()-Z  
tGravityAcc-std()-X  
tGravityAcc-std()-Y  
tGravityAcc-std()-Z  
tBodyAccJerk-mean()-X  
tBodyAccJerk-mean()-Y  
tBodyAccJerk-mean()-Z  
tBodyAccJerk-std()-X  
tBodyAccJerk-std()-Y  
tBodyAccJerk-std()-Z  
tBodyGyro-mean()-X  
tBodyGyro-mean()-Y  
tBodyGyro-mean()-Z  
tBodyGyro-std()-X  
tBodyGyro-std()-Y  
tBodyGyro-std()-Z  
tBodyGyroJerk-mean()-X  
tBodyGyroJerk-mean()-Y  
tBodyGyroJerk-mean()-Z  
tBodyGyroJerk-std()-X  
tBodyGyroJerk-std()-Y  
tBodyGyroJerk-std()-Z  
tBodyAccMag-mean()  
tBodyAccMag-std()  
tGravityAccMag-mean()  
tGravityAccMag-std()  
tBodyAccJerkMag-mean()  
tBodyAccJerkMag-std()  
tBodyGyroMag-mean()  
tBodyGyroMag-std()  
tBodyGyroJerkMag-mean()  
tBodyGyroJerkMag-std()  
fBodyAcc-mean()-X  
fBodyAcc-mean()-Y  
fBodyAcc-mean()-Z  
fBodyAcc-std()-X  
fBodyAcc-std()-Y  
fBodyAcc-std()-Z  
fBodyAcc-meanFreq()-X  
fBodyAcc-meanFreq()-Y  
fBodyAcc-meanFreq()-Z  
fBodyAccJerk-mean()-X  
fBodyAccJerk-mean()-Y  
fBodyAccJerk-mean()-Z  
fBodyAccJerk-std()-X  
fBodyAccJerk-std()-Y  
fBodyAccJerk-std()-Z  
fBodyAccJerk-meanFreq()-X  
fBodyAccJerk-meanFreq()-Y  
fBodyAccJerk-meanFreq()-Z  
fBodyGyro-mean()-X  
fBodyGyro-mean()-Y  
fBodyGyro-mean()-Z  
fBodyGyro-std()-X  
fBodyGyro-std()-Y  
fBodyGyro-std()-Z  
fBodyGyro-meanFreq()-X  
fBodyGyro-meanFreq()-Y  
fBodyGyro-meanFreq()-Z  
fBodyAccMag-mean()  
fBodyAccMag-std()  
fBodyAccMag-meanFreq()  
fBodyBodyAccJerkMag-mean()  
fBodyBodyAccJerkMag-std()  
fBodyBodyAccJerkMag-meanFreq()  
fBodyBodyGyroMag-mean()  
fBodyBodyGyroMag-std()  
fBodyBodyGyroMag-meanFreq()  
fBodyBodyGyroJerkMag-mean()  
fBodyBodyGyroJerkMag-std()  
fBodyBodyGyroJerkMag-meanFreq()  
 
###Data

Dataset: Human Activity Recognition Using Smartphones

The dataset contain:
- 'features_info.txt': Shows information about the variables used on the feature vector.  
- 'features.txt': List of all features.  
- 'activity_labels.txt': Links the class labels with their activity name.  
- 'train/X_train.txt': Training set.  
- 'train/y_train.txt': Training labels.  
- 'test/X_test.txt': Test set.  
- 'test/y_test.txt': Test labels.  
- 'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.  
- 'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis.   
- 'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration.  
- 'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.  

Transformations

The script 'run_analysis.R' make the following transformations to Human Activity Recognition Using Smartphones dataset:

1.	Extract from 'features.txt' only features with mean and standard deviation for each measurement.  
2.	Put column names from 'features.txt' to 'test/X_test.txt'.  
3.	Extract from 'test/X_test.txt' only the measurements on the mean and standard deviation for each measurement.  
4.	Bind files subject_test, y_test and X_test.  
5.	Put column names from 'features.txt' to 'train/X_train.txt'.  
6.	Extract from 'train/X_train.txt' only the measurements on the mean and standard deviation for each measurement.  
7.	Bind files subject_train, y_train and X_train.  
8.	Merge test and train data using rbind and melt function.  
9.	Put id labels: "subject", "Activity_ID"and "Activity_Label" to the the merge data.  
10.	Apply mean function to dataset using dcast function.  
11.	Write table 'tidy_data.txt'.  
