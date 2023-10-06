# mysql_cloudmanaged_databases
homework 4

## Setup process for GCP
Go to console.cloud.google.com and check that are in stonybrook.edu account  
Create a new project in AHI-GCP folder called chevi-504-hw4  
Go to sql in menu, and create an instance, choose MySQL, and enable API  
Create an instance ID, password, choose enterprise, sandbox, shared core, and lower CPU  
In connections, Allow all for name and wildcard network of 0.0.0.0/0  
make sure the cost is very low ~$.01 per day  
Create the instance  
IP address 35.202.156.109

## Experience with MySQL Workbench
Was unable to download the most updated version of Workbench. After trying to use popsql and trying to update my computer, downloaded an older version of Workbench. The first one I tried did not work, but the second one did.  
Created an instance called gcp hw 4 instance, and connected it to the IP address 35.202.156.109
created a database called chevi
Was able to create the ERD in the chevi database using the sample code in the 504 Github repo.


![Screen Shot 2023-10-05 at 21 33 14](https://github.com/chebbin/mysql_cloudmanaged_databases/assets/141374142/e4df299b-3e51-4e31-ab40-2babb8ad94c7)


## Setup process for Azure
Setup Stonybrook Account  
Select Azure Database for MySQL  
Choose Flexible deployment option  
Create new Resource Group in Azure for students hw4RG  
server name 504hw4instance  
setup username cebbin and password  
Change compute to B1S for $6.21/month  
In networking choose AlloAll for wildcard network of 0.0.0.0/0  
Create Instance  
subscription ID 9373fa3c-3610-4046-8b51-f77250d60e6b  

## Connection to MySQL Workbench
Instructions found when clicking on Connect on the instance Overview page  
Used 504hw4instance.mysql.database.azure.com as hostname as per instruction  
Created the ERD in the chevi database using the sample code in the 504 Github repo  


![Screen Shot 2023-10-05 at 21 18 41](https://github.com/chebbin/mysql_cloudmanaged_databases/assets/141374142/5c0da1d3-f62d-4600-b7b1-5de27b237203)

