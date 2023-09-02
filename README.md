# BotitTask

# Technologies used:
MEAN stack

This project was generated with Angular CLI version 16.2.3 and Node.js version v18.17.1


To run node: node backend/server.js

To run angular: ng serve

The uri to the database I created: 'mongodb+srv://bassantthossam:BH1234@cluster0.gwvwumj.mongodb.net/?retryWrites=true&w=majority'
But I have to add the IP address, so that the database can be accessed.

# 4 Frontend components: 
1. Home

2. Products: display the products list, can edit any product and can add product

3. Create-product: shows the data of the product you wish to edit or if you want to add product you can add it from this page (contains some validations)

4. Order: display the orders list, can cancel any product (maximum 3 days after the order date, or the cancel button will be invisible)


# 3 Backend JS files:
1. Server.js

2. Rest.js: which contains all the API requests

3. Db.js: which contains the schemas of the two collections
Note: To add a new order, it can be added in the backend. I commented the part that is needed to add a new order (in the db.js). 
