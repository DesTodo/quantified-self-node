## Quantified Self Backend App: API Endpoints replicated from Rails using Node.js

### This is the backend part of an app to provide data and endpoints for a single user calory tracking application; it is built in NodeJS and Express. 
To access the the client side app built with jQuery: [https://jf-lalonde.github.io/quantified-self/foods] [https://jf-lalonde.github.io/quantified-self/] 

  **To Run Locally**
  *1.Clone this repo*
  *2.Install Node Packages*
  ```npm init
  npm i express --save
  npm install nodemon --save-dev
  npm install knex pg --save
  npm install knex -g ``` 
  
  *3.Setup Database*
  ```$ psql
  CREATE DATABASE foods;
  CREATE DATABASE meals;
  knex migrate:latest
  knex seed:run```
