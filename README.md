# Getting-and-Cleaning-Data-Course-Project
Coursera Project
The R script titled: "run_analysis.R", performs the following operations, 

1. Download the dataset of interest if it does not already exist in the working directory 
2. Load the activity and feature info
 3. Loads both the training and test datasets but only keeps the columns that depict a mean or a standard deviation
 4. It loads the activity and subject data for each dataset and merges those
 columns with the dataset
 5. Merges the two datasets
 6. Converts the "activity" and "subject" columns into factors
 7. Creates a tidy dataset that consists of the average value of each
 variable for each subject and activity pair.
 
This result is shown in the file named "tidy.txt".
