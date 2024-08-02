BFHL Challenge

This is a full-stack application developed for the Bajaj Finserv Health Dev Challenge (Qualifier 1). The application consists of a backend API built with Node.js and Express.js, and a frontend application built with React.js.

Backend API

The backend API is deployed on Heroku and can be accessed at https://your-heroku-app-name.herokuapp.com/bfhl.

The API has two endpoints:

POST /bfhl: Accepts a JSON payload with a data array and returns a response with the processed data.
GET /bfhl: Returns a hardcoded response with an operation_code of 1.
Frontend Application

The frontend application is deployed on Vercel and can be accessed at https://bfhl-challenge.vercel.app.

The application allows users to input a JSON payload and submit it to the backend API. The response is then displayed on the frontend, with options to filter the data by alphabets, numbers, and highest alphabet.

Development

To develop the application, clone the repository and run the following commands:

npm install to install dependencies
npm start to start the development server
Deployment

To deploy the application, follow these steps:

Deploy the backend API to Heroku using git push heroku master
Deploy the frontend application to Vercel using the Vercel CLI
