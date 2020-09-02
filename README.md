# Preprocessing-a-data-set
Getting and Cleaning Data
The data set used is obtained from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
This is a solution to the peer graded assignment of the course Getting and Cleaning Data on Coursera.
# Step 1: Getting the data.
First download the zip file containing the data and unzip the zip file.
Then read the data.
# Step 2: Merging the data.
Merge the training and test data sets to create one data set.
First concatenate the  two data sets to create a single table then remove the individual tables.
# Step 3: Extract measurements.
First determine the columns whose measurements will be used for calculating standard deviation and mean.
Then keep a track of those data.
# Step 4: Name activities in the data sets.
Replace activity values with named factor levels.
# Step 5: Label the data set.
First get the column names.
Then remove special charactersand typos and expand abbreviations.
Then rename the columns.
# Step 6: Create a second tidy set. 
First group by using subject and activity.
Then summarize using mean.
Then create a txt file created with write.table() using row.name=FALSE.
