# This is the code book that describe the variables

#Data Set Analysis
Human Activity Recognition Using Smartphones Dataset

"The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data". 

"The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details". 

For each record it is provided:
Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
Triaxial Angular velocity from the gyroscope. 
A 561-feature vector with time and frequency domain variables. 
Its activity label. 
An identifier of the subject who carried out the experiment.



# Directory and filename (txt or csv) of the clean/tidy data:
"./tidy-UCI-HAR-dataset.txt"
"./tidy-UCI-HAR-dataset-AVG.csv"
# Directory and filename (.txt) of the clean/tidy data
"./tidy-UCI-HAR-dataset-AVG.txt"

# The result is saved as "./tidy-UCI-HAR-dataset-AVG.txt"
This is a 180x68 data table (181 with column name), where as before, the first column contains subject IDs, the second column contains activity names (see below), and then the averages for each of the 66 attributes are in columns 3...68. There are 30 subjects and 6 activities, thus 180 rows in this data set with averages.