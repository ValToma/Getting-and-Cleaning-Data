Codebook 

Variable Description

X, Y, Z: the axis of X, Y and Z (signals can be in the X, Y and Z directions) 

t (at the beginning of the variable names): time domain signals 

f (at the beginning of the variable names): frequency domain signals 

mean: Mean value 

std: Standard deviation 

meanFreq: Weighted average of the frequency components to obtain a mean 
frequency 
angle: Angle between to vectors 
Acc: Acceleration signal from the smartphone accelerometer (sensor signal). 
Gyr: Angular velocity from the smartphone gyroscope (sensor signal). 
Body: The signals related to the body of subject (individual) who has been examined. 
Jerk: Jerk signals (the body linear acceleration and angular velocity were derived in 
time to reach this signal) 
Mag: magnitude of the three-dimensional signals calculated using the Euclidean norm 
Gravity: The signals related to the gravity. 
Subject: The numbers between 1 to 30 which are identifiers of the subjects 
(individuals) who carried out the experiment. 
Activity: including 6 activities performed by subjects (STANDING, SITTING, 
LAYING, WALKING, WALKING_DOWNSTAIRS, WALKING_UPSTAIRS) 
Data set and transformations 
The data set was obtained in the form of several txt files from the link below provided in the assignment instructions:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The dataset includes the following files:
'README.txt'
'features_info.txt': Shows information about the variables used on the feature vector.
'features.txt': List of all features.
'activity_labels.txt': Links the class labels with their activity name.
'train/X_train.txt': Training set.
'train/y_train.txt': Training labels.
'test/X_test.txt': Test set.
'test/y_test.txt': Test labels.
The following files are available for the train and test data.
'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.
'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis.
'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration.
'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.
