# Products_REST_API-Project
Introduction:
Backend development is typically the first step after the planning phase of the creation of a new application. The frontend application is dependent on the backend server’s data and functionality. This is an exercise of building a backend Web API prior to the start of the frontend of the application. We will be testing and interacting with this backend Web API using Postman to ensure everything is working as expected. This will also help us visualize what the structure of the data will be that the frontend will be consuming. 

Learning Objectives: Understand how to build a Web API for a full-stack application with database integration. 

Task: Create a Django REST API connected to a MySQL database allowing a frontend application to POST comments and replies to the MySQL database relative to the video the user is currently watching.
<><><><><><><><><><><><><><><><><><><><><><><><>

<!-- Total points: /55 unweighted -> /5 weighted
(/5 points): As a developer, I want to make good, consistent commits. -->

<!-- (/2.5 points) As a developer, I want to create a Product model
Property names must be in snake_case and match the following exactly!
• title - CharField
• description - CharField
• price - DecimalField
• inventory_quantity – IntegerField -->

<!-- (/2.5 points) As a developer, I want my API to serve content on the following urls
paths:
Paths must match these exactly!
• ‘127.0.0.1:8000/api/products/'
• ‘127.0.0.1:8000/api/products/<int:pk>/’ -->

<!-- (/15 points) As a developer, I want to build a REST web API in Django REST
Framework, so that I can make HTTP requests interact with the data set. -->

<!-- (/5 points) As a developer, I want to create a GET endpoint the responds with a
200 success status code and all of the products within the Product table. -->

(/5 points) As a developer, I want to create a GET by id endpoint that does the
following things:
• Accepts a value from the request’s URL (The id of the product to retrieve).
• Returns a 200 status code.
• Responds with the product in the database that has the id that was sent
through the URL.

(/5 points) As a developer, I want to create a POST endpoint that does the
following things:
• Accepts a body object from the request in the form of a Product model.
• Adds the new product to the database.
• Returns a 201 status code.
• Responds with the newly created product object.

(/5 points) As a developer, I want to create a PUT endpoint that does the
following things:
• Accepts a value from the request’s URL (The id of the product to be
updated).
• Accepts a body object from the request in the form of a Product model.
• Finds the product in the Product table and updates that product with the
properties that were sent in the request’s body.
• Returns a 200 status code.
• Responds with the newly updated product object.

(/5 points) As a developer, I want to create a DELETE endpoint that does the
following things:
• Accepts a value from the request’s URL.
• Returns a 204 status code (NO CONTENT).

(/5 points) As a developer, I want to use Postman to make a POST, PUT, DELETE,
and both GET requests (get by id and get all) request to my REST web API, save it
to a collection, and then export it as a JSON from Postman.

BONUS
(/5 points) As a developer, I want to add the ability to add an image link to each
product. (Link to picture on the internet, this will just be a simple CharField
representing the URL of the image, you do NOT need to add an actual image
file.)