Process
Both train and test data were divided into 3 tables: x = features, y = activity and subject = subject. 
All the data were merged in one dataset.
From this dataset we extracted only columns with mean and SD values, activity and subject.
the number in column "activity" were replaced with a description available in the activity column of the original dataset.
The original variables names, such as tBodyAccMag-mean(), were replaced with better descriptive names.
An independent tidy data set was created with the mean of each activity and each subject. 
This new dataset was saved in the tidy_data.txt file.
