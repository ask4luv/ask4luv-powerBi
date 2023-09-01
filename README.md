## Ask4luv-POWERBI

1.TO LOAD DATA INTO POWER BI:
###### Open Power BI Desktop.
###### From "Home" tab click on "Get Data".
###### Select your data sources for "Employee", "Department", and "Salary". All this Excel files are CSV files.

2.TRANSFORM DATA USING POWER QUERY EDITOR:
###### After loading the datasets, I entered into the Power Query Editor, by clicking the "Edit Queries" button in the Home tab.
###### From there I commenced the data cleansing by removing the unwanted datas and null values. Below is the Pictures
<img width="958" alt="1" src="https://github.com/ask4luv/ask4luv-powerBi/assets/138107435/1121351c-0fb4-4493-b05c-f65d1f6938ad">

<img width="958" alt="2" src="https://github.com/ask4luv/ask4luv-powerBi/assets/138107435/41611431-4db6-46f2-8751-99b8203b47fa">

<img width="960" alt="3" src="https://github.com/ask4luv/ask4luv-powerBi/assets/138107435/13574797-29f9-4a1d-902f-a8fe2fd0b8ac">

3.MERGE QUERIES BASED ON COMMON KEY:
###### There is a single dataset containing the three individual datasets, which can be merge with other datasets using a common key.
###### Select the combined dataset and click on "Home" -> "Merge Queries".
###### The second and the third dataset which are Department and salary are to be merged and select the common key columns for merging. Choosen the default join to merge the datasets.
###### Once the merge is done, the merged columns name (combine Table) from the merged dataset will be added to your combined dataset.

4.APPLY CHANGES AND LOAD DATA:

###### After all necessary merges are performed, click on "Close & Apply" in the Power Query Editor to apply the changes and load the merged data into your Power BI data model.

<img width="960" alt="4" src="https://github.com/ask4luv/ask4luv-powerBi/assets/138107435/4374dedb-78a9-4e2b-9c68-026b6be65f01">


