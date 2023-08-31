# CMPG323-Project2-35689765

# EcoPower Logistics

The EcoPower Logistics Project is aimed at (Create,Read,Update,Delete) RESTful API that connects a database, helping in storing logistics data.The API works as a backend system that manages information related to customers,orders and more.

# Features

- Create:Allows for the adding of new data to the database.
- Read:Receives data from the database.
- Update:Allows for the changing of exisiting data in the database.
- Delete:Allows for the removal of selected data in the database.

# How StakeHolders Are To Use The Report That Is Developed

Stakeholders can use the EcoPower Logistics API for numerous purposes like:
- For mananging data,they can create,read,update and delete data using the API.
- Reports can be generated from using the data in the database.
- Intergrating the API with other existing systems and applications for logistics processing 
- Testing and developing of logistics related features and applications.
  
# The List of Endpoints to be Implemented

Customers Resource:

- GET /api/customers: Get a list of all customers.
- GET /api/customers/{id}: Get details of a specific customer by ID.
- POST /api/customers: Create a new customer.
- PUT /api/customers/{id}: Update an existing customer by ID.
- DELETE /api/customers/{id}: Delete a customer by ID.

Products Resource:

- GET /api/products: Get a list of all products.
- GET /api/products/{id}: Get details of a specific product by ID.
- POST /api/products: Create a new product.
- PUT /api/products/{id}: Update an existing product by ID.
- DELETE /api/products/{id}: Delete a product by ID.

Orders Resource:

- GET /api/orders: Get a list of all orders.
- GET /api/orders/{id}: Get details of a specific order by ID.
- POST /api/orders: Create a new order.
- PUT /api/orders/{id}: Update an existing order by ID.
- DELETE /api/orders/{id}: Delete an order by ID.
