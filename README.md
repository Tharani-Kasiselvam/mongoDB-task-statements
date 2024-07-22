#MONGODB Statements for below Questions   
1.	Find all the information about each products - ***find()***   
2.	Find the product price which are between 400 to 800 - ***find()***, ***$and,$gte***   
3.	Find the product price which are not between 400 to 600 - ***find()***, ***$and,$gte,$lte,$ne***   
4.	List the four product which are greater than 500 in price - ***find()***, ***$gte***, ***limit()***   
5.	Find the product name and product material of each products - ***find({},{...fields...})*** [specific fields]   
6.	Find the product with a row id of 10 - ***find({...id...})*** [specific id]   
7.	Find only the product name and product material - ***find({},{...fields...})*** [specific fields]   
8.	Find all products which contain the value of soft in product material - ***find({...field...})*** [specific field]   
9.	Find products which contain product color indigo  and product price 492.00 -  ***find()***, ***$and***   
10.	Delete the products which product price value are 28 - ***deleteOne()***   

***Author : Tharani K***
