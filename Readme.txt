
 
  Project Title: ETL Pipeline that Copies Data from Source Folder to Target Folder Within the Azure Data Lake

A.  Source Folder Details:
	 Number of Files: 2
	 File format: CSV

B.  Output Folder Details:
	 Number of Files: None

	

C.  Business requirements:
    Client (user) needed to Copy Data from a Source Folder to Target Folder Within the Azure Data Lake
	

D.  Solution Steps: 
   	 -create RBAC role assignment for the storage account container 
   	 -create link service, datasets, ETL pipeline and activities
   	 -Copy files from source folder to the output folder
   	 -check the output folder for the copied data to confirm the pipeline runs successfully


E.  Azure Services used: 
   	 -Azure Data Lake
   	 -Azure Data Factory

