# ETL-for-SCD-Type-1-
ETL with Pentaho (Slowly Changing Dimension)
There are 7 different types of data changes in dimension data in the data warehouse. 
The first type is type 0. Changes are not accepted. And that's why I didn't start with it. 
SCD type 1 is a method that updates the data by changing it.
![image](https://github.com/SuleymanSamandov/ETL-for-SCD-Type-1-/assets/98223056/3942b78a-b0eb-490c-b1d9-2e9f7feb5027)

# How does updating data work? 
The data update process is implemented using a method called "Upsert".
This process works by updating if there is data, otherwise insert. 
And the SQL equivalent is the Merge function.
![image](https://github.com/SuleymanSamandov/ETL-for-SCD-Type-1-/assets/98223056/16884b5f-dce1-404e-a1f6-b632b7c3b7bb)
