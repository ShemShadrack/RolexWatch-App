# RolexWatch-App
The project is composed of a Web Application (Already developed in previous work on the project), a desktop application (already developed but will be optimized and updated), these last two are linked to backend database (MySQL), and a mobile application that is going to be implemented together with a backend database (SQLite) and synchronized with the MySQL one. 
This functional requirements section will be mainly about the mobile application but will also touch the desktop application that will take care of the management of orders, accounts and products. It is dedicated for the administrator of the system.  

## MOBILE APPLICATION: 
### Register: 
The user of the application must be able to create an account. While creating his account, he must provide personal info: Name, address, email address, phone number… He will have to confirm his email address. 
Login: 
The mobile application must have login activity with a field for a username and a password. The user will be able to login if he confirmed his email address. After logging in, the user will be able to: 
-view/modify his personal info. 
-view latest products. 
-add products to a cart.  
-remove product from a cart.  
-view the cart. 
-confirm an order. 
 
 
### Home:
The mobile application must have a home screen visible for all the user of the application (whether logged in or not). The home screen should contain the latest products added to the database.  
Search:  
The mobile application should have a screen for product search based on some criteria: 
-	Price 
-	Name 
-	Brand 
### User Account:  
The user must be able to modify his personal information and terminate his account if he has no pending orders. 
Products: 
The user of the application must be able to view a product list available for sale. He must be able to view their details and add them to his cart if he is logged in. 
### Orders: 
 After adding products to his cart, the user must be able to confirm his order and provide a valid address and a valid mobile phone for the products to be shipped.  
### Push Notifications:  
The mobile application could have a push notifications functionality. It will be used to send promotions to users. It could also be used to inform users about new products. 
### About:  
The mobile application should have a screen dedicated for general information about the company. 

### Desktop Application
The desktop application (already implemented) is a database management system dedicated for the administrator to:  
-	Manage the accounts of users registered through the mobile application or the web application.  
-	Manage the products that will be displayed in the web and mobile application. 
-	Manage the orders made through the mobile or web application. 
It must have the following functional requirements: 
