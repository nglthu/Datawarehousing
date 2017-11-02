# Datawarehousing
# Project title: 
	
Data Warehousing Project  Building and Analysing a DW
for NF Stores in NZ 
![alt text](https://github.com/nglthu/Datawarehousing/blob/master/img/dataIntegration.png)



# Getting Started:

The project will include four files:

1. createDW.sql
 To create the schema of the Project

2. INLJ.sql
 It includes extract, transform, and load records to DW

3. queriesDW.sql
 It contains all OLAP queries

4. projectReport.doc
 It reports the whole process.

========================================================

# STEP BY STEP to operate the project:

==================
## A. Connection
==================
1. Open the SQL developer 


2. Connect to the Oracle server:
 
	
======================
## B. Unzip the folder
======================

3. Download All files

4. ReadMe for futher information

================================
## C. Run files on sql developer
================================

5. First, run createDW.sql to construct the star schema



6. Second, run INLJ.sql 
 
	to perform extract records from the transaction, 
 
	transform these with master data, 
 
	then load these record to DW.



7. Third, run queriesDW.sql for the DW analysis 2017

	#### Run from line 2 to line 9 for Q1
	```
	To see the highest sale in the whole year
	```
	#### Run from line 10 to line 23 for Q2
	```
	To see three supplier names in Aug 2016 in terms of total sales
	```
	#### Run from line 24 to line 37 for Q3
	```
	 To determine 3 store names in Aug 2016 in terms of total sales
	```
	#### Run from line 40 to line 52 for Q4
	```
	 To see how many sales transaction for the product that generates max sales in 2016
	```
	#### Run from line 56 to line 79 for Q5
	```
  	To present quarterly sale analysis for all products using drill-down query concepts
	```
 	#### Run from line 83 to line 94 for Q6
	```
 	To create a materialised view with name "STOREANALYSIS_MV"  to present product-wise sales for each store
	```
	#### Run from line 99 to line 111 for Rollup of Q7a
	```
    To see other information retrieved from Q6 with rollup  
	```
	#### Run from line 112 to 125 for Cube of Q7b
	```
	To see other information retrieved from Q6 with cube concept 

	```

