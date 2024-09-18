# AWSproject-Aakash

# Objective Project 1 

In Project 1, I aimed to use the data of the migration of the City of Vancouver data to an AWS cloud platform. The focus of this project is to build an efficient data analytics pipeline, which will provide better infrastructures for processing, analyzing, and visualizing data for various departments of the city. The emphasis will be on scalability and security. Using the cloud infrastructure, the project would strive towards smoothing out the data management of the city for easy access and decision-making. It will help in seamlessly handling big volumes of data, which include advanced analytics and insight visualizations, through a scalable and secure system that will meet the increasing needs of the city's data.



# Table of Contents 

   •	Methodology

   •	Data Discovery

   •	Data Pipeline Design

   •	Data Analysis

   •	Data Visualisation

   •	Data Publishing


Methodology 

Data Analytical Question Formulation 

Data for the years 2022 and 2023 were dug into, showing the metric called "Awarded Contracts." The metric will show the percentage of calls handled in the years 2022 and 2023, respectively.



![image](https://github.com/user-attachments/assets/ae1f1fce-00dc-456a-9207-237afcbf1089)

Data Discovery 
Concentrated on the process of 'Awarded Contracts Metrics' inside the Government and Finance division of the city of Vancouver.

Below is the data utilized for the project1.  

![image](https://github.com/user-attachments/assets/db2275d2-715d-4c32-914c-ce7769097491)


Data Storage Design 

Safe data storage was achieved by using Amazon S3, where data was classified into three stages: Landing, Raw, and Curated. 

  •	Dataset Preparation 

  •	Data Collection

  •	ETL processes

  •	Data cleaning using AWS Glue DataBrew 


Data Pipeline Design 

For Data processing  Draw.io is being used.

![image](https://github.com/user-attachments/assets/0257cc26-3f5f-4985-bcff-3b04436560b5)

![image](https://github.com/user-attachments/assets/c8f15782-77b3-41da-9c92-63e8b7e68f9c)


Data Analysis 

Executed utilizing AWS Athena for querying and providing valuable information.

  •	AWS Services

  •	Amazon S3 for storage

  •	EC2 for computation

  •	AWS Glue for ETL processes

  •	Athena for data analysis.




Data Pipeline Implementation


  •	Utilized AWS Glue for Extended Transaction Lifetime (ETL) operations.


  •	These transformation processes included schema modifications, aggregate, and union actions.


  •	To modify the structure of the 2022 and 2023 dataset, all unnecessary columns have been removed and the columns BID_ID, Year, Awarded, and Award Category  have been retained and renamed. 


  •	An aggregate operation has been used to combine the entries of the 'Year' column in the dataset for the years 2022 and 2023.


  •	In order to generate a combined dataset from the records of 2022 and 2023, the Union function has been used to produce a new output by combining all the records from the two comparable input datasets. 


At this point, undesired columns have been removed using the alter schema procedure. 
Derived Column: The matrix is computed at this step by executing the SQL function. Successfully managed awarded contracts


![image](https://github.com/user-attachments/assets/1022cd1e-0baf-42f1-b140-df65dedcec22)

Data Analysis 

  •	The data analysis was conducted utilizing AWS Athena architecture. 
  
  •	Analysis of the dataset content was conducted using a SQL database.

Below is the data derived from the database of  AWS Athena:  

![image](https://github.com/user-attachments/assets/fd126d31-9e87-4167-b612-d5ae68a14f29)


Result 

  •	Amazon EC2 was used to establish a General Server and Web Server for both internal and external data access.
  
  •	Issued the yearly analysis report detailing the proportion of Awarded Contracts for public access.

![image](https://github.com/user-attachments/assets/a1708f30-8488-4c7d-ac8b-a97ed3288a50)

Insights and Findings 3

In 2022, the 'Awarded contract' for the City of Vancouver achieved a call handling rate of 285, therefore demonstrating a commendable level of efficiency in award management. 
The proportion of calls managed decreased somewhat to 285.

This decreases, however insignificant, suggests a little deterioration in the efficiency of processing calls compared to the prior year. 

Between 2022 and 2023, there is a significant decline in the proportion of awarded contracts effectively managed. This may be attributed to many things, including a surge in bid category or difficulties in allocating resources.


Costing 

For Team Assignment 1 our detailed team assignment costing is mentioned below as per the AWS services used by every team member:

  •	Amazon S3: Estimated annual expense of $285.846 for storage across four buckets.

  •	AWS Glue DataBrew: Estimated yearly cost of $32.04 for cleaning and restructuring datasets.

  •	AWS Glue: Estimated total cost of $13.20 for ETL job runs.

  •	Amazon Athena: Estimated annual expense of $35.76 for querying and analysis.

  •	EC2: Total yearly cost of $225.96 for hosting general and web servers.

Conclusion
This study demonstrates the efficacy of using AWS cloud services for extensive data analytics and emphasizes the potential to automate data processes and obtain valuable insights for urban administration.



# Project 2 

The process for the consideration of surveys is administered by the Survey Management Committee, a group of faculty and staff with knowledge and experience in survey methodology and design and related topics


# Table of Contents

•	Methodology

•	Data Discovery

•	Data Pipeline Design

•	Data Analysis

•	Data Visualisation

•	Data Publishing

Data Analytical Question Formulation (Methodology)

This policy and associated procedure outline the coordinated approach to the administration of surveys with the goal of maximizing their usefulness


Dataset Discovery

The sample dataset includes three Excel files for the years 2022, 2023 & 2024

•	Sample Survey Records Information.  

•	Sample Survey Records. 

•	Sample completed survey


Data Pipeline Design
•	For Data processing  Draw.io is being used.


AWS Services
•	For Data Storage Amazon S3.
•	For Data Cleaning and Structuring AWS GlueData Brew.
•	For Data Pipeline structure AWS Glue.

Data Cleaning and Structuring includes some different types of operations for different easy working such as: 

•	Checking invalid values in data sets such as null rows.

•	Renaming of column names.

•	Change of Data Type for columns.

•	Change of Schema (Addition of Column as required).

•	Creation and publishing of recipes.


![image](https://github.com/user-attachments/assets/57ecf86c-4413-4a29-9e19-527eac3901f6)


Data Pipeline Implementation:

•	Implemented using AWS Glue for ETL processes.

•	Transformation operations included schema changes, aggregation, and union operations.


![image](https://github.com/user-attachments/assets/98452711-5038-4db5-a799-23133c2a4d9f)

Outcome

They ETL  diagram illustrating the calculation of metrics derived by ETL Glue.


Insights and Findings

•	Survey Success rate for the year 2024:

o	The survey rate for the year 2023 is 70 %.

o	This indicates that for every 10 surveys generated in the year 2024, 7 were successful.

o	This rate reflects an increase when compared to the previous years (2022 & 2023).

•	Survey Success rate for the year 2023:

o	The graduation rate for the year 2023 is 50%.

o	This indicates that for every 10 surveys generated in the year 2023, 5 were successful.  

o	However, this rate reflects a decrease of 5% when compared to the previous years (2022).

•	Survey Success rate for the year 2022:

o	The graduation rate for the year 2022 is 55%.

o	This indicates that for every 10 surveys generated in the year 2022, 5.5 were successful.  



•	Trend Analysis:

o	There is a notable fluctuation in the graduation rates over the three years:

o	2022: 55%

o	2023: 50% (5% increase from 2022)

o	2024: 70% (20%  increase from 2023)

•	The observed pattern underscores possible areas of worry in the survey success rate that UCW should consider resolving.


Conclusion

•	The project efficiently utilizes AWS Glue DataBrew for data cleansing and transformation, and the ETL pipeline is successfully implemented to compute the graduation rate of students.


•	The whole process, from data preparation to the creation of final output, is meticulously structured with explicit procedures for extracting, converting, and loading data into an S3 bucket. By using a systematic data processing technique. 


•	The project intends to give insights on university survey success rate. The outlined pipeline illustrates a thorough methodology to accomplish this goal.# AWSproject-Aakash-Sharma
