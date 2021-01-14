#CODEBOOK

Data

The tidy_data.txt data file is a text file, containing space-separated values.

The first row contains the column names which are the variables for which data was captured. The following rows contain the values of these variables.

Variables

Each row contains, for a given subject and activity, 79 signal measurements which are means of the original data set provided which can be found at 

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip.


Identifiers

SUBJECT

Subject identifiers are integers referring to a person and range from 1 to 30.

ACTIVITY

Activity identifier, string with 6 possible values:

1 WALKING

2 WALKING_UPSTAIRS

3 WALKING_DOWNSTAIRS

4 SITTING

5 STANDING

6 LAYING


Time-domain signals

Average time-domain body acceleration in the X, Y and Z directions:
timeDomainBodyAccelerometerMeanX
timeDomainBodyAccelerometerMeanY
timeDomainBodyAccelerometerMeanZ

Standard deviation of the time-domain body acceleration in the X, Y and Z directions:
timeDomainBodyAccelerometerStandardDeviationX
timeDomainBodyAccelerometerStandardDeviationY
timeDomainBodyAccelerometerStandardDeviationZ

Average time-domain gravity acceleration in the X, Y and Z directions:
timeDomainGravityAccelerometerMeanX
timeDomainGravityAccelerometerMeanY
timeDomainGravityAccelerometerMeanZ

Standard deviation of the time-domain gravity acceleration in the X, Y and Z directions:

timeDomainGravityAccelerometerStandardDeviationX
timeDomainGravityAccelerometerStandardDeviationY
timeDomainGravityAccelerometerStandardDeviationZ

Average time-domain body acceleration jerk (derivation of the acceleration in time) in the X, Y and Z directions:

timeDomainBodyAccelerometerJerkMeanX
timeDomainBodyAccelerometerJerkMeanY
timeDomainBodyAccelerometerJerkMeanZ

Standard deviation of the time-domain body acceleration jerk (derivation of the acceleration in time) in the X, Y and Z directions:

timeDomainBodyAccelerometerJerkStandardDeviationX
timeDomainBodyAccelerometerJerkStandardDeviationY
timeDomainBodyAccelerometerJerkStandardDeviationZ

Average time-domain body angular velocity in the X, Y and Z directions:

timeDomainBodyGyroscopeMeanX
timeDomainBodyGyroscopeMeanY
timeDomainBodyGyroscopeMeanZ

Standard deviation of the time-domain body angular velocity in the X, Y and Z directions:

timeDomainBodyGyroscopeStandardDeviationX
timeDomainBodyGyroscopeStandardDeviationY
timeDomainBodyGyroscopeStandardDeviationZ

Average time-domain body angular velocity jerk (derivation of the angular velocity in time) in the X, Y and Z directions:

timeDomainBodyGyroscopeJerkMeanX
timeDomainBodyGyroscopeJerkMeanY
timeDomainBodyGyroscopeJerkMeanZ

Standard deviation of the time-domain body angular velocity jerk (derivation of the angular velocity in time) in the X, Y and Z directions:

timeDomainBodyGyroscopeJerkStandardDeviationX
timeDomainBodyGyroscopeJerkStandardDeviationY
timeDomainBodyGyroscopeJerkStandardDeviationZ

Average and standard deviation of the time-domain magnitude of body acceleration:

timeDomainBodyAccelerometerMagnitudeMean
timeDomainBodyAccelerometerMagnitudeStandardDeviation

Average and standard deviation of the time-domain magnitude of gravity acceleration:

timeDomainGravityAccelerometerMagnitudeMean
timeDomainGravityAccelerometerMagnitudeStandardDeviation

Average and standard deviation of the time-domain magnitude of body acceleration jerk (derivation of the acceleration in time):

timeDomainBodyAccelerometerJerkMagnitudeMean
timeDomainBodyAccelerometerJerkMagnitudeStandardDeviation

Average and standard deviation of the time-domain magnitude of body angular velocity:

timeDomainBodyGyroscopeMagnitudeMean
timeDomainBodyGyroscopeMagnitudeStandardDeviation

Average and standard deviation of the time-domain magnitude of body angular velocity jerk (derivation of the angular velocity in time):

timeDomainBodyGyroscopeJerkMagnitudeMean
timeDomainBodyGyroscopeJerkMagnitudeStandardDeviation

Frequency-domain signals

Average frequency-domain body acceleration in the X, Y and Z directions:

frequencyDomainBodyAccelerometerMeanX
frequencyDomainBodyAccelerometerMeanY
frequencyDomainBodyAccelerometerMeanZ

Standard deviation of the frequency-domain body acceleration in the X, Y and Z directions:

frequencyDomainBodyAccelerometerStandardDeviationX
frequencyDomainBodyAccelerometerStandardDeviationY
frequencyDomainBodyAccelerometerStandardDeviationZ

Weighted average of the frequency components of the frequency-domain body acceleration in the X, Y and Z directions:

frequencyDomainBodyAccelerometerMeanFrequencyX
frequencyDomainBodyAccelerometerMeanFrequencyY
frequencyDomainBodyAccelerometerMeanFrequencyZ

Average frequency-domain body acceleration jerk (derivation of the acceleration in time) in the X, Y and Z directions:

frequencyDomainBodyAccelerometerJerkMeanX
frequencyDomainBodyAccelerometerJerkMeanY
frequencyDomainBodyAccelerometerJerkMeanZ

Standard deviation of the frequency-domain body acceleration jerk (derivation of the acceleration in time) in the X, Y and Z directions:

frequencyDomainBodyAccelerometerJerkStandardDeviationX
frequencyDomainBodyAccelerometerJerkStandardDeviationY
frequencyDomainBodyAccelerometerJerkStandardDeviationZ

Weighted average of the frequency components of the frequency-domain body acceleration jerk (derivation of the acceleration in time) in the X, Y and Z directions:

frequencyDomainBodyAccelerometerJerkMeanFrequencyX
frequencyDomainBodyAccelerometerJerkMeanFrequencyY
frequencyDomainBodyAccelerometerJerkMeanFrequencyZ

Average frequency-domain body angular velocity in the X, Y and Z directions:

frequencyDomainBodyGyroscopeMeanX
frequencyDomainBodyGyroscopeMeanY
frequencyDomainBodyGyroscopeMeanZ

Standard deviation of the frequency-domain body angular velocity in the X, Y and Z directions:

frequencyDomainBodyGyroscopeStandardDeviationX
frequencyDomainBodyGyroscopeStandardDeviationY
frequencyDomainBodyGyroscopeStandardDeviationZ

Weighted average of the frequency components of the frequency-domain body angular velocity in the X, Y and Z directions:

frequencyDomainBodyGyroscopeMeanFrequencyX
frequencyDomainBodyGyroscopeMeanFrequencyY
frequencyDomainBodyGyroscopeMeanFrequencyZ

Average, standard deviation, and weighted average of the frequency components of the frequency-domain magnitude of body acceleration:

frequencyDomainBodyAccelerometerMagnitudeMean
frequencyDomainBodyAccelerometerMagnitudeStandardDeviation
frequencyDomainBodyAccelerometerMagnitudeMeanFrequency

Average, standard deviation, and weighted average of the frequency components of the frequency-domain magnitude of body acceleration jerk (derivation of the acceleration in time):

frequencyDomainBodyAccelerometerJerkMagnitudeMean
frequencyDomainBodyAccelerometerJerkMagnitudeStandardDeviation
frequencyDomainBodyAccelerometerJerkMagnitudeMeanFrequency

Average, standard deviation, and weighted average of the frequency components of the frequency-domain magnitude of body angular velocity:

frequencyDomainBodyGyroscopeMagnitudeMean
frequencyDomainBodyGyroscopeMagnitudeStandardDeviation
frequencyDomainBodyGyroscopeMagnitudeMeanFrequency

Average, standard deviation, and weighted average of the frequency components of the frequency-domain magnitude of body angular velocity jerk (derivation of the angular velocity in time):

frequencyDomainBodyGyroscopeJerkMagnitudeMean
frequencyDomainBodyGyroscopeJerkMagnitudeStandardDeviation
frequencyDomainBodyGyroscopeJerkMagnitudeMeanFrequency

HOW THE SCRIPT TRANSFORMS THE ORIGINAL DATA - this info is available in the README.md

LIST OF ALL PARAMETERS

 "subject"                                    "tBodyAccelerometerMeanX"                   
 [3] "tBodyAccelerometerMeanY"                    "tBodyAccelerometerMeanZ"                   
 [5] "tBodyAccelerometerStandardDeviationX"       "tBodyAccelerometerStandardDeviationY"      
 [7] "tBodyAccelerometerStandardDeviationZ"       "tGravityAccelerometerMeanX"                
 [9] "tGravityAccelerometerMeanY"                 "tGravityAccelerometerMeanZ"                
[11] "tGravityAccelerometerStandardDeviationX"    "tGravityAccelerometerStandardDeviationY"   
[13] "tGravityAccelerometerStandardDeviationZ"    "tBodyAccelerometerJerkMeanX"               
[15] "tBodyAccelerometerJerkMeanY"                "tBodyAccelerometerJerkMeanZ"               
[17] "tBodyAccelerometerJerkStandardDeviationX"   "tBodyAccelerometerJerkStandardDeviationY"  
[19] "tBodyAccelerometerJerkStandardDeviationZ"   "tBodyGyroscopeMeanX"                       
[21] "tBodyGyroscopeMeanY"                        "tBodyGyroscopeMeanZ"                       
[23] "tBodyGyroscopeStandardDeviationX"           "tBodyGyroscopeStandardDeviationY"          
[25] "tBodyGyroscopeStandardDeviationZ"           "tBodyGyroscopeJerkMeanX"                   
[27] "tBodyGyroscopeJerkMeanY"                    "tBodyGyroscopeJerkMeanZ"                   
[29] "tBodyGyroscopeJerkStandardDeviationX"       "tBodyGyroscopeJerkStandardDeviationY"      
[31] "tBodyGyroscopeJerkStandardDeviationZ"       "tBodyAccelerometerMagMean"                 
[33] "tBodyAccelerometerMagStandardDeviation"     "tGravityAccelerometerMagMean"              
[35] "tGravityAccelerometerMagStandardDeviation"  "tBodyAccelerometerJerkMagMean"             
[37] "tBodyAccelerometerJerkMagStandardDeviation" "tBodyGyroscopeMagMean"                     
[39] "tBodyGyroscopeMagStandardDeviation"         "tBodyGyroscopeJerkMagMean"                 
[41] "tBodyGyroscopeJerkMagStandardDeviation"     "fBodyAccelerometerMeanX"                   
[43] "fBodyAccelerometerMeanY"                    "fBodyAccelerometerMeanZ"                   
[45] "fBodyAccelerometerStandardDeviationX"       "fBodyAccelerometerStandardDeviationY"      
[47] "fBodyAccelerometerStandardDeviationZ"       "fBodyAccelerometerMeanFrequencyX"          
[49] "fBodyAccelerometerMeanFrequencyY"           "fBodyAccelerometerMeanFrequencyZ"          
[51] "fBodyAccelerometerJerkMeanX"                "fBodyAccelerometerJerkMeanY"               
[53] "fBodyAccelerometerJerkMeanZ"                "fBodyAccelerometerJerkStandardDeviationX"  
[55] "fBodyAccelerometerJerkStandardDeviationY"   "fBodyAccelerometerJerkStandardDeviationZ"  
[57] "fBodyAccelerometerJerkMeanFrequencyX"       "fBodyAccelerometerJerkMeanFrequencyY"      
[59] "fBodyAccelerometerJerkMeanFrequencyZ"       "fBodyGyroscopeMeanX"                       
[61] "fBodyGyroscopeMeanY"                        "fBodyGyroscopeMeanZ"                       
[63] "fBodyGyroscopeStandardDeviationX"           "fBodyGyroscopeStandardDeviationY"          
[65] "fBodyGyroscopeStandardDeviationZ"           "fBodyGyroscopeMeanFrequencyX"              
[67] "fBodyGyroscopeMeanFrequencyY"               "fBodyGyroscopeMeanFrequencyZ"              
[69] "fBodyAccelerometerMagMean"                  "fBodyAccelerometerMagStandardDeviation"    
[71] "fBodyAccelerometerMagMeanFrequency"         "fBodyAccelerometerJerkMagMean"             
[73] "fBodyAccelerometerJerkMagStandardDeviation" "fBodyAccelerometerJerkMagMeanFrequency"    
[75] "fBodyGyroscopeMagMean"                      "fBodyGyroscopeMagStandardDeviation"        
[77] "fBodyGyroscopeMagMeanFrequency"             "fBodyGyroscopeJerkMagMean"                 
[79] "fBodyGyroscopeJerkMagStandardDeviation"     "fBodyGyroscopeJerkMagMeanFrequency"        
[81] "activity"                                  
