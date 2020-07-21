Getting-and-Cleaning-Data-Proj

This repository contains 3 files: run_analysis.R, CodeBook.rmd, and FinalData.txt

run_analysis.R retrieves dthe zipfile on "Human Activity Recognition in Smartphones", unzips the file, and creates the necessary datasets from the unzipped file.

The datasets are then tidied up by:

1. Merging variables to create a single dataset

2. Extracting the mean and standard deviation for each measurement

3. Applying descriptive activities to the activity variable

4. Applying descriptive names to the variables

5. Creating a second dataset that contains the averages for each variable

CodeBook.rmd contains more detailed information into how this process is completed. 

FinalData.txt contains the exported dataset that has gone through the above steps.
