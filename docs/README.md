# EDA



# Architecture -expenses tracking

![alt text](https://wittline.github.io/uber-expenses-tracking/Images/architecture.png)


## What are the data sources?

<p align="justify"> 
Every time an Ubers Eat or Uber Rides service has ended, you will receive a payment receipt to your email, this receipt contains the information about the details of the service, and is attached to the email with the extension <strong>.eml</strong>. Both receipts belong to the details sent by Uber about Eats and Rides services, this will be our original data sources.

</p>



## Data modelling

<p align="justify"> 
Once the details for each type of receipt have been detected, it is easy to know what are the features, entities, and relations of the model. My proposed data model contains the expenses of both services separated in different fact tables.

</p>

 
![alt text](https://wittline.github.io/uber-expenses-tracking/Images/dwh_schema.jpg)


 
![alt text](https://wittline.github.io/uber-expenses-tracking/Images/dag.PNG)



 
</p>



![powerBi_uber_services6](https://user-images.githubusercontent.com/8701464/115949563-97e22b00-a49b-11eb-92ab-5459b4469f5f.gif)




