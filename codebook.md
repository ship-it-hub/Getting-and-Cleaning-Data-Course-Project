---
title: "CODEBOOK"
output:
  md_document:
    variant: markdown_github
---

# Codebook

## Data changes

The input  data has been changed using the script *run_analysis.R* which has the following steps:
1. merging the training and the test sets to create one data set;
2. extracting only the measurements on the mean and standard deviation for each measurement;
3. using descriptive activity names to name the activities in the data set;
4. appropriately labeling the data set with descriptive variable names;
5. creating a second, independent tidy data set with the average of each variable for each activity and each subject.

## Data description

The first two variables are used to identify observations:
* Subject - the ID of the Subject;
* Activity - the name of the activity performed by the subject.
* The variables remaining are the calculated means and standard deviations of input data:
* TimeBodyAccelerometer.mean X                     
* TimeBodyAccelerometer.mean Y                     
* TimeBodyAccelerometer.mean Z                     
* TimeGravityAccelerometer.mean X                  
* TimeGravityAccelerometer.mean Y                  
* TimeGravityAccelerometer.mean Z                  
* TimeBodyAccelerometerJerk.mean X                 
* TimeBodyAccelerometerJerk.mean Y                 
* TimeBodyAccelerometerJerk.mean Z                 
* TimeBodyGyroscope.mean X                         
* TimeBodyGyroscope.mean Y                         
* TimeBodyGyroscope.mean Z                         
* TimeBodyGyroscopeJerk.mean X                     
* TimeBodyGyroscopeJerk.mean Y                     
* TimeBodyGyroscopeJerk.mean Z                     
* TimeBodyAccelerometerMagnitude.mean              
* TimeGravityAccelerometerMagnitude.mean           
* TimeBodyAccelerometerJerkMagnitude.mean          
* TimeBodyGyroscopeMagnitude.mean                  
* TimeBodyGyroscopeJerkMagnitude.mean              
* FrequencyBodyAccelerometer.mean X                
* FrequencyBodyAccelerometer.mean Y                
* FrequencyBodyAccelerometer.mean Z                
* FrequencyBodyAccelerometer.meanFreq X            
* FrequencyBodyAccelerometer.meanFreq Y            
* FrequencyBodyAccelerometer.meanFreq Z            
* FrequencyBodyAccelerometerJerk.mean X            
* FrequencyBodyAccelerometerJerk.mean Y            
* FrequencyBodyAccelerometerJerk.mean Z            
* FrequencyBodyAccelerometerJerk.meanFreq X        
* FrequencyBodyAccelerometerJerk.meanFreq Y        
* FrequencyBodyAccelerometerJerk.meanFreq Z        
* FrequencyBodyGyroscope.meanX
* FrequencyBodyGyroscope.meanY
* FrequencyBodyGyroscope.meanZ
* FrequencyBodyGyroscope.meanFreqX
* FrequencyBodyGyroscope.meanFreqY
* FrequencyBodyGyroscope.meanFreqZ
* FrequencyBodyAccelerometerMagnitude.mean
* FrequencyBodyAccelerometerMagnitude.meanFreq
* FrequencyBodyAccelerometerJerkMagnitude.mean
* FrequencyBodyAccelerometerJerkMagnitude.meanFreq
* FrequencyBodyGyroscopeMagnitude.mean
* FrequencyBodyGyroscopeMagnitude.meanFreq
* FrequencyBodyGyroscopeJerkMagnitude.mean
* FrequencyBodyGyroscopeJerkMagnitude.meanFreq
* Angle.TimeBodyAccelerometerMean.Gravity
* Angle.TimeBodyAccelerometerJerkMeanGravityMean
* Angle.TimeBodyGyroscopeMean.GravityMean
* Angle.TimeBodyGyroscopeJerkMean.GravityMean
* Angle.X.GravityMean
* Angle.Y.GravityMean
* Angle.Z.GravityMean
* TimeBodyAccelerometer.stdX
* TimeBodyAccelerometer.stdY
* TimeBodyAccelerometer.stdZ
* TimeGravityAccelerometer.stdX
* TimeGravityAccelerometer.stdY
* TimeGravityAccelerometer.stdZ
* TimeBodyAccelerometerJerk.stdX
* TimeBodyAccelerometerJerk.stdY
* TimeBodyAccelerometerJerk.stdZ
* TimeBodyGyroscope.stdX
* TimeBodyGyroscope.stdY
* TimeBodyGyroscope.stdZ
* TimeBodyGyroscopeJerk.stdX
* TimeBodyGyroscopeJerk.stdY
* TimeBodyGyroscopeJerk.stdZ
* TimeBodyAccelerometerMagnitude.std
* TimeGravityAccelerometerMagnitude.std
* TimeBodyAccelerometerJerkMagnitude.std
* TimeBodyGyroscopeMagnitude.std
* TimeBodyGyroscopeJerkMagnitude.std
* FrequencyBodyAccelerometer.stdX
* FrequencyBodyAccelerometer.stdY
* FrequencyBodyAccelerometer.stdZ
* FrequencyBodyAccelerometerJerk.stdX
* FrequencyBodyAccelerometerJerk.stdY
* FrequencyBodyAccelerometerJerk.stdZ
* FrequencyBodyGyroscope.stdX
* FrequencyBodyGyroscope.stdY
* FrequencyBodyGyroscope.stdZ
* FrequencyBodyAccelerometerMagnitude.std
* FrequencyBodyAccelerometerJerkMagnitude.std
* FrequencyBodyGyroscopeMagnitude.std
* FrequencyBodyGyroscopeJerkMagnitude.std 