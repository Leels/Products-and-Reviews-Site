# products_reviews_database
## By: Lela Smith

### Description
#### Database tracker for specialty food products store. The database uses a one to many relationship to track products (which have a product name, cost, and country of origin) and each product's reviews (which have an author, content_body and rating).

### Project Specs
#### Landing Page
##### The landing page contains basic information about the company and allows users to easily navigate to other areas of the site. This page also includes the three most recently added products and the product with the most reviews.

#### Products
* The site includes a products section with a list of the products. Each product is clickable with a detail view.

* Users are able to add, update and delete new products.
Users should be able to click an individual product to see its detail page. (You will not be expected to show the product's average rating. That's included in the further exploration section.)
Users should be able to add a review to a product.
Scopes
Your site should use scopes to display the following information on the site:

The product with the most reviews.
The three most recently added products.
All products made in the USA for buyers that want to buy local products.
Validations
Your site should include validations for the following:

All fields should be filled out, including rating.
Rating can only be an integer between 1 and 5.
The review's content_body must be between 50 and 250 characters.
Callbacks
Your site should include a callback for the following:

All products are automatically titleized (first letter of each word capitalized) before they are saved to the database.
Seeding
Your project should include seed data for 50 products and 250 reviews. Use Faker with a loop to seed the database.
Flash Messages
The project should include flash success and error messages for creating products and reviews.

### Project Routes
|HTTP verb|Route|CRUD Action|Description|
|---|---|---|---|
|GET|/products|READ|Get list of products|
|GET|/products/:id|READ|Look at detail page for a single product|
|POST|/products|CREATE|Add new product to the list of products|
|PATCH|/products/:id|UPDATE|Update a single product|
|DELETE|/products/:id|DELETE|Delete a product from the list|
|GET|/products/new|READ|Go to the form page for adding a new product to the list|
|GET|/products/:id/edit|READ|Go to the form page for editing a product


|HTTP verb|Route|CRUD Action|Description|
|---|---|---|---|
|GET|/products/:id/reviews/:review_id|READ|Look at detail page for a single review|
|POST|/products/:id/reviews/:review_id|CREATE|Add new review to the list of reviews|
|PATCH|/products/:id/reviews/:review_id|UPDATE|Update a single review|
|DELETE|/products/:id/reviews/:review_id|DELETE|Delete a review from the list|

### Known Bugs
#### None

### Setup
* Download Postgres
* Clone this repository:
* from  _C:\Users\exampleUser\exampleCloneLocation\example-project-title>_
1. $ bundle install


### Technologies Used
* HTML
* CSS
* Bootstrap
* Ruby
* Rails
* Bootstrap
* Sinatra
* PostgreSQL

### License
#### This software is licensed under the MIT license.

#### Copyright (c) 2019 Lela Smith
