# E-Commerce-Back-End

## Description

I was contacted by an e-commerce firm who wanted to modernize their backend routing. In order to remain competitive, the data that customers want must be readily available and easily accessible. The work that I have done on the back-end will make the job of the front-end developers much easier. My database modelling and relationship mapping allows front-end developers easy access to a wealth of useful information in which to build out the front-end view. For example, instead of writing seperate database queries for products, categories, and tags, my implementation provides all of that data in one query and in one object response.

When making this project I learned the importance of creating a strong model folder to bring the database schema to life. Using the model files to fully initiate the tables and then using the corresponding index.js file to establish the relationships, implementing the routing becomes a much simpler and more rewarding effort. The tools provided by the Sequelize package a very advantageous.

## Installation

In order to install the app, begin by cloning this repo to your local machine. Remember to install all dependencies. You will need node and MySQL installed on your machine as well.

## Usage

To use the app, first ensure you have the required databse by sourcing the schema.sql file in MySQL. After that, please run `npm run seed` or `node seeds/` to load your database with data. Whne you have test data, use `npm start` or a similar command to launch the app.

With the app running, head over to Insomnia and run the following paths to view and maniuplate the data:

Category:
 - GET /api/categories/ 
 - GET /api/categories/:id
 - POST /api/categories
 - PUT /api/categories/:id
 - DELETE /api/categories/:id

 Product:
 - GET /api/products/
 - GET /api/products/:id
 - POST /api/products
 - PUT /api/products/:id
 - DELETE /api/products/:id

 Tag:
 - GET /api/tags/
 - GET /api/tags/:id
 - POST /api/tags
 - PUT /api/tags/:id
 - DELETE /api/tags/:id

![GIF displaying a user accessing the routes listed above in Insomia](./assets/Walkthrough_GIF.gif)

[Video of the GIF above](./assets/Walkthrough_Video.webm)
