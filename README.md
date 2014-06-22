Tidy_data_assignment
====================

Running the script

1. Download the data set and extract. It should result in a UCI HAR Dataset folder that has all the files in the required structure.
2. Change current directory to the UCI HAR Dataset folder.
3. Run Rscript <path to>/run_analysis.R
4. The tidy dataset should get created in the current directory as tidy.txt


Assumptions

1. The training and test data are available in folders named train and test respectively.
2. For each of these data sets:
    - Measurements are present in X_<dataset>.txt file
    - Subject information is present in subject_<dataset>.txt file
    - Activity codes are present in y_<dataset>.txt file
3. All activity codes and their labels are in a file named activity_labels.txt.
4. Names of all measurements taken are present in file features.txt ordered and indexed as they appear in the X_<dataset>.txt files.
5. All columns representing means contain ...mean() in them.
6. All columns representing standard deviations contain ...std() in them.
