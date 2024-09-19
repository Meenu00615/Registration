# Full Stack Registration Form Project 
   ### https://meenu00615.github.io/Registration/

## Overview

This project is a full-stack web application that implements a user registration form. The application is built using HTML, CSS, Node.js, Express.js, and MongoDB. The goal is to create a seamless and secure user registration process, storing user information in a MongoDB database.

## Technologies Used

- **HTML and CSS**: The front end of the application is built with HTML for structuring the web pages and CSS for styling.

- **Node.js**: The server-side logic is implemented using Node.js, providing a JavaScript runtime environment.

- **Express.js**: Express.js is used as the web application framework for Node.js, simplifying the process of handling HTTP requests and responses.

- **MongoDB**: MongoDB is employed as the database system for storing user registration data. It offers a flexible and scalable NoSQL database solution.

## Tools and Libraries

- **[Express Validator](https://express-validator.github.io/docs/)**: Used for validating and sanitizing user input on the server-side.

- **[Mongoose](https://mongoosejs.com/)**: A MongoDB object modeling tool for Node.js, used for interacting with the MongoDB database in an easier way.

- **[dotenv](https://www.npmjs.com/package/dotenv)**: A zero-dependency module that loads environment variables from a `.env` file into `process.env`.

## Features

1. **User Registration Form**: The application provides a user-friendly registration form where users can enter their information.

2. **Validation**: Client-side and server-side validation mechanisms ensure that the entered data is accurate and secure.

3. **Database Storage**: User registration details are securely stored in a MongoDB database, allowing for efficient retrieval and management.

## Getting Started

Follow these steps to set up and run the project on your local machine:

1. **Clone the repository**:
   
 -->  ```bash
   
 --> git clone https://github.com/varshakodati/registration-form.git
   
2.**Install dependencies**: 

 --> cd registration-form
   
 --> npm install

3.**Configure MongoDB connection**:

 --> Create a .env file in the root directory.

 --> Add your MongoDB connection string as MONGODB_URI.

4.**start the application**:

 --> npm start

## Deployment

This project is designed to be hosted on [Render](https://render.com/). Follow these steps to deploy the project:

1.Create an account on Render.

2.Initialize a Git repository if not already done.

--> git init

3.Create a new web service on Render:

--> Connect your GitHub repository to Render.

--> Set up environment variables, including the MongoDB URI.

4.Deploy the application:

--> Render will automatically build and deploy your application when changes are pushed to the connected repository.

5.Open the deployed app using the provided URL.

--> Adjust the instructions based on the specific hosting/rendering platform you've used. Replace "your-mongodb-uri" with the actual MongoDB connection string and include any platform-specific details.


## Result:

The registration form application successfully captures user data and stores it in a MongoDB database. Validation mechanisms ensure the integrity of the data, providing a secure and user-friendly experience.

![image](https://github.com/user-attachments/assets/2703d809-ab7b-4cfd-a548-db559b4fa721)


## Future Work:
Improved UI.
Additional Form Fields: Expand the registration form with additional fields based on project requirements.
Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and improvements are highly appreciated!
