Challenge: The first issue we faced was the spread nature of CSV files, and some of the files were recorded in a new format, which was in the Nova folder structure. 

Approach: the approach we took was to vertically combine those CSV files. Used the pandas data frame feature to combine all the monthly CSV files for each city. So in step one, we combined all the months data into one CSV for one City. Then step two, we combined all the City CSV into a single CSV.


Challenge: the second challenge we faced was regarding the changed schema of the new vendor. The file format is also different from csv (i.e jsonl)

While we were uploading the raw data into the repository, we could not uplad it directly because the file was larger than 25 mb. To solve this, we use Github LFS. 
