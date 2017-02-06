## The contents of "tidydata.txt"
The data set "tidydata.txt" contains the averages of certain variables from the original data set, calculated over the distinct combinations of activities (1-6) and subjects (1-30). Consequently, there are 180 rows of data in the data set (excluding the header).

The data set contains averages 66 variables, plus the 2 variables "activity" and "subject" over which the averages were computed. That makes 68 columns in total. These variables whose averages were computed and their counterparts in the original data set "features.txt". 

| Name in tidydata.txt | Name in features.txt | 
|------------ | -------------|
| BodyAccXmean | tBodyAcc-mean()-X | 
| BodyAccYmean | tBodyAcc-mean()-Y| 
| BodyAccZmean | tBodyAcc-mean()-Z | 
| BodyAccXstd | tBodyAcc-std()-X | 
| BodyAccYstd | tBodyAcc-std()-Y | 
| BodyAccZstd | tBodyAcc-std()-Z | 
| GravityAccXmean | tGravityAcc-mean()-X | 
| GravityAccYmean | tGravityAcc-mean()-Y | 
| GravityAccZmean | tGravityAcc-mean()-Z | 
| GravityAccXstd | tGravityAcc-std()-X | 
| GravityAccYstd | tGravityAcc-std()-Y | 
| GravityAccZstd | tGravityAcc-std()-Z | 
| BodyAccJerkXmean | tBodyAccJerk-mean()-X| 
| BodyAccJerkYmean | tBodyAccJerk-mean()-Y| 
| BodyAccJerkZmean | tBodyAccJerk-mean()-Z| 
| BodyAccJerkXstd | tBodyAccJerk-std()-X|
| BodyAccJerkYstd | tBodyAccJerk-std()-Y| 
| BodyAccJerkZstd | tBodyAccJerk-std()-Z| 
| BodyGyroXmean | tBodyGyro-mean()-X| 
| BodyGyroYmean | tBodyGyro-mean()-Y| 
| BodyGyroZmean | tBodyGyro-mean()-Z| 
| BodyGyroXstd | tBodyGyro-std()-X|
| BodyGyroYstd | tBodyGyro-std()-Y|
| BodyGyroZstd | tBodyGyro-std()-Z|
| BodyGyroJerkXmean | tBodyGyroJerk-mean()-X|
| BodyGyroJerkYmean | tBodyGyroJerk-mean()-Y|
| BodyGyroJerkZmean | tBodyGyroJerk-mean()-Z|
| BodyGyroJerkXstd | tBodyGyroJerk-std()-X|
| BodyGyroJerkYstd | tBodyGyroJerk-std()-Y|
| BodyGyroJerkZstd | tBodyGyroJerk-std()-Z|
| BodyAccMagmean | tBodyAccMag-mean()|
| BodyAccMagstd | tBodyAccMag-std()|
| GravityAccMagmean | tGravityAccMag-mean()|
| GravityAccMagstd | tGravityAccMag-std()|
| BodyAccJerkMagmean | tBodyAccJerkMag-mean()|
| GravityAccJerkMagstd | tBodyAccJerkMag-std()|
| BodyGyroMagmean | tBodyGyroMag-mean()|
| BodyGyroMagstd | tBodyGyroMag-std()|
| BodyGyroJerkMagmean | tBodyGyroJerkMag-mean()|
| BodyGyroJerkMagstd | tBodyGyroJerkMag-std()|
| FreqBodyAccXmean | fBodyAcc-mean()-X|
| FreqBodyAccYmean | fBodyAcc-mean()-Y|
| FreqBodyAccZmean | fBodyAcc-mean()-Z|
| FreqBodyAccXstd | fBodyAcc-std()-X|
| FreqBodyAccYstd | fBodyAcc-std()-Y|
| FreqBodyAccZstd | fBodyAcc-std()-Z|
| FreqBodyAccJerkXmean | fBodyAccJerk-mean()-X|
| FreqBodyAccJerkYmean | fBodyAccJerk-mean()-Y|
| FreqBodyAccJerkZmean | fBodyAccJerk-mean()-Z|
| FreqBodyAccJerkXstd | fBodyAccJerk-std()-X|
| FreqBodyAccJerkYstd | fBodyAccJerk-std()-Y|
| FreqBodyAccJerkZstd | fBodyAccJerk-std()-Z|
| FreqBodyGyroXmean | fBodyGyro-mean()-X|
| FreqBodyGyroYmean | fBodyGyro-mean()-Y|
| FreqBodyGyroZmean | fBodyGyro-mean()-Z|
| FreqBodyGyroXstd | fBodyGyro-std()-X|
| FreqBodyGyroYstd | fBodyGyro-std()-Y|
| FreqBodyGyroZstd | fBodyGyro-std()-Z|
| FreqBodyAccMagmean | fBodyAccMag-mean()|
| FreqBodyAccMagstd | fBodyAccMag-std()|
| FreqBodyAccJerkMagmean | fBodyBodyAccJerkMag-mean()|
| FreqGravityAccJerkMagstd | fBodyBodyAccJerkMag-std()|
| FreqBodyGyroMagmean | fBodyBodyGyroMag-mean()|
| FreqBodyGyroMagstd | fBodyBodyGyroMag-std()|
| FreqBodyGyroJerkMagmean | fBodyBodyGyroJerkMag-mean()|
| FreqBodyGyroJerkMagstd | fBodyBodyGyroJerkMag-std()|

###Note on the units
The data in "tidydata.txt" is average over the aforementioned variables in X_train.txt and X_test.txt files. Note that the data in those files is normalized and bounded between [-1,1].

