# E-Commerce-ORM-Repo

## Description
This application is designed to be an E-Commerce backend application that uses Object-Relational Mapping (ORM). Run entirely on the backend, a user can view all of their inventory including products, tags, and categories of their business. I was insipred to make this to give managers at an internet retail company an e-commerce website that uses the latest backend technologies so their company can competewith other e-commerce companies. Since the application is run entirely on the backend, please refer to my walkthrough video within the README. The E-Commerce ORM utilized backend technologies like Node.JS, MySQL, and Sequelize in order to get the application running smoothly. Testing of the routes was done via the Insomnia application.

## Installation

To open this environment, here are the steps needed:

1. Open Terminal
2. Make a new directory titled "e-commerce-orm" (ensure you are in the location on your computer where you want the repo to be)
3. In GitHub, click the green 'Code' button and copy the HTTPS link
4. In Terminal, type "git clone" then paste the copied link and hit enter
5. Once cloned, check the status of the cloning by navigating to the directory where the repo is located and typing "git status"
6. If green, then the repo has been cloned and you can then drag the folder from your computer into vscode to run the environment

## Usage 
You may use this to view and add any tags, products or categories to your e-commerce inventory. In ordet to run this application, please run the following commands within your terminal once the repo has been cloned:
  1. npm i
  2. Navigate to the db database and enter: mysql -u root -p (enter your mysql password)
  3. Once MySQL is running, enter: source schema.sql;
  4. Navigate out of the db and enter: npm run seed
  5. Finally, enter: node server

## Walkthrough Video

https://drive.google.com/file/d/162wRAD7SqJLLG0iTX9f7lF4cCq9yWa9t/view

## Credits 
Thank you to third party websites like MDN and W3 for providing me with lots of information to complete this assignment. Thank you as well to MySQL and  Sequelize for providing the necessary functions to allow this application to work.
