### Quantified Self Backend:

Backend app providing API endpoints and data for a single user calory tracking application.It is built with NodeJS and Express. 

[Access client side app built with jQuery: foods](https://jf-lalonde.github.io/quantified-self/foods) 

[Access client side app built with jQuery: meals](https://jf-lalonde.github.io/quantified-self/)

  **To Run Locally**
  
  *1.Clone this repo*
  
  *2.Install Node Packages*
  
  ```npm init
  npm i express --save
  npm install nodemon --save-dev
  npm install knex pg --save
  npm install knex -g
  ```
  
  *3.Setup Database*
  
  ```$ psql
  CREATE DATABASE foods;
  CREATE DATABASE meals;
  knex migrate:latest
  knex seed:run
  ```
