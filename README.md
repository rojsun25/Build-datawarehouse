# Build-traditional datawarehouse-datamarts
Using SQL/Python - oracle developer

### Design STAR SCHEMA
Before exporting the data, a sample table is created and created the star schema design with the given 
details,

1. ->CREATE ->Table -> Added few tables for designing the schema.
2. -> DATABASE TOOLS -> Relationships -> establish connection between dimension and fact table using 
the primary and foreign key.

![image](https://user-images.githubusercontent.com/84145744/169697161-cc0158fc-fc98-4244-ab0f-19098e663ad7.png)

### Steps to build datawarehouse

1. Extract the waterquality dataset using Microsft Access where it consists of 17 years of samples taken from the various location.
2. ODBC driver to interact with the access and SQL DEVELOPER transform entire dataset.
3. Explore the data and anlayse 
4. First Implement Dimension table using cursor method as per the sample model
5. After - Implement FACT TABLE using CURSOR method 

![image](https://user-images.githubusercontent.com/84145744/169695982-0a48dac6-0be4-4590-af44-24ea63b4ca4b.png)


### Connecting cx_Oracle TO jupyter notebook
1. Establishing a connection between cx_Oracle to Jupyter using the package: !pip install cx_Oracle.
2. Connect to the oracle_client reading the library directory. 
3. Connect to host ‘’ using the credentials user and password.

Link: https://drive.google.com/file/d/1BDDKL6tcljx7K61Tu8xKR_4ukp8qZ93o/view?usp=sharing

![cx_Oracle_arch](https://user-images.githubusercontent.com/84145744/169854677-86df9c02-73e4-4182-95c6-0dfac985fbf0.png)

### Machine learning models

















