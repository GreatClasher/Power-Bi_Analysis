# EDA



# Architecture -expenses tracking

![alt text](https://wittline.github.io/uber-expenses-tracking/Images/architecture.png)


## What are the data sources?

<p align="justify"> 
Every time an Ubers Eat or Uber Rides service has ended, you will receive a payment receipt to your email, this receipt contains the information about the details of the service, and is attached to the email with the extension <strong>.eml</strong>. Take a look at the image below, both receipts belong to the details sent by Uber about Eats and Rides services, this will be our original data sources, In my case, I downloaded all those receipts from my email to my local computer.

</p>



## Data modelling

<p align="justify"> 
Once the details for each type of receipt have been detected, it is easy to know what are the features, entities, and relations of the model. My proposed data model contains the expenses of both services separated in different fact tables, sharing dimensions between these facts, therefore, the proposed model will be a constellation scheme.

</p>

 
![alt text](https://wittline.github.io/uber-expenses-tracking/Images/dwh_schema.jpg)


 
![alt text](https://wittline.github.io/uber-expenses-tracking/Images/dag.PNG)


## Visualizing AWS Redshift data using Microsoft Power BI

<p align="justify">
Now, you will connect Power BI Desktop to AWS Redshift data, create a dashborad for Uber Eats and Uber Rides, publish the report to Power BI service, and you can consume the report from your mobile device as well.
 
</p>

- Launch Power BI Desktop
- Sign in to the Service with your Power BI credentials
- Select Home -> Get Data -> More > Database -> Amazon Redshift
- Click Connect
- On the next screen, provide the following values: Server, Database and Data Connectivity Mode (Import)
- Build your dashboards, in this case there are already two dashboards with several reports on it and you can use the same example below on the file **report_receipts.pbix**
- Update your redshift cluster, it will change


![powerBi_uber_services6](https://user-images.githubusercontent.com/8701464/115949563-97e22b00-a49b-11eb-92ab-5459b4469f5f.gif)




