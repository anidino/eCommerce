# eCommerce! 

## User Story
* AS A manager at an internet retail company
* I WANT a back end for my e-commerce website that uses the latest technologies
* SO THAT my company can compete with other e-commerce companies 

## User Criteria 
* GIVEN a functional Express.js API
* WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
* THEN I am able to connect to a database using Sequelize
* WHEN I enter schema and seed commands
* THEN a development database is created and is seeded with test data
* WHEN I enter the command to invoke the application
* THEN my server is started and the Sequelize models are synced to the MySQL database
* WHEN I open API GET routes in Insomnia Core for categories, products, or tags
* THEN the data for each of these routes is displayed in a formatted JSON
* WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
* THEN I am able to successfully create, update, and delete data in my database

## Technologies Used
* Node
* Express
* MySQL2 
* Sequelize 
* dotenv package 
* nodemon 

## Installation & Usage 
After acquiring the needed dependencies & setting up the files, adding the missing routes and models, and logging into mySQL via Workbench, I ran 'npm run seed' which allowed me to seed my database with the information from the seeds.js files. After doing this, I was able to run 'node server' and see a successful connection. Then, I used Insomia to test the GET, POST, PUT, DELETE routes. 

## Acknowledgements
The commented area of my code in the Models directory, Index.js file was given to me in class by my instructor, Gabe Perry. 
[https://github.com/Gperry22](Github) 

## Video Demo Part I - npm run seed & node server 


## Video Demo Part II - test all routes in Insomia 
