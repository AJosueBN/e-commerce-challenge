# week-13-e-commerce-challenge

Building the backend for an e-commerce site. Technologies involved in this project include JavaScript, Express, APIs and will configure it to use Sequelize to interact with a MySQL database and initialising data between the models/routes.

This will be done through:
- Sourcing queries within MySQL
- Syncing Sequelize to the database on server start
- Seeding database into the models and the routes
- Testing data functionality in an API platform

# Things added/implemented to the task of modifying backend data:

Able to connect through to the database using Sequelize once adding in the name of the database, the MySQL username and the MySQL password to an environment variable file.
Data is seeded with the created development database once you enter schema and seed commands:
- Schema command: source db/schema.sql;  Seed command: npm run seed
- Server can start(npm run start) and models are synced 
- Able to test API requests for categories, products or tags and create, update, or delete data from the database.

# Video of functionality of different types of API requests

https://github.com/AJosueBN/week-13-e-commerce-challenge/assets/129113539/5e97afdb-78d2-4f60-bd88-9dabb3923b6c

- Data that is passed through the API platform from the video above forms from syncing Sequelize with the database that is on MySQL and seeding it into the data that has been gathered so that the user is able to test routes through requests.
