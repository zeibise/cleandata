#Producing a clean data set from the source data
##Steps:
1. Read the source files to the R:
	* test/X_test.txt
	* train/X_train.txt
	* test/y_test.txt
	* train/y_train.txt
	* test/subject_test.txt
	* train/subject_train.txt
2. Combine the data from files "test/X_test.txt" and "train/X_train.txt". The data in these files is stored in row format without any headers or footers, so the rows in the train data can be directly appended to the rows in the test data.
3. The treatment from Step 2 was reproduced for the data in files "test/y_test.txt" and "train/y_train.txt".
4. The data obtained in Step 3 was converted to factor, and the levels were manually given the names from the file "activity_labels.txt". These are:
	* 1 Walking
	* 2 Walking upstairs
	* 3 Walking downstairs
	* 4 Sitting
	* 5 Standing
	* 6 Laying
5. The treatment from step 2. was repeated for the data from files "test/subject_test.txt" and "train/subject_train.txt".
6. The variables that are either mean or standard deviation of a measurement were extracted. These are the rows from the "features.txt" that contain the phrase "mean()"or "std()".
7. The labels and subject information obtained in steps 4. and 5., respectively, were added to the data obtained in step 6.
8. The data obtained in step 7 were hand-crafted a descriptive name.
9. The mean of the variables gathered in step 6. were computed over the distinct pairs of activities and subjects. The resulting data was written to the file "tidydata.txt"
# cleandata
