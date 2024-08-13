# Registration Form Project

## Overview
This project is a full-stack web application for user registration, built with HTML, CSS, Node.js, Express.js, and MongoDB. The application focuses on creating a seamless and secure registration process, with user information stored in a MongoDB database.

## Technologies Used
- **HTML & CSS**: Structure and style the front end.
- **Node.js**: Server-side logic.
- **Express.js**: Simplifies HTTP requests and responses.
- **MongoDB**: NoSQL database for storing user data.

## Tools & Libraries
- **Express Validator**: Server-side input validation and sanitization.
- **Mongoose**: Simplifies interaction with MongoDB.
- **dotenv**: Loads environment variables from `.env`.

## Features
- **User Registration Form**: User-friendly interface for data entry.
- **Validation**: Ensures data accuracy and security.
- **Database Storage**: Securely stores registration details in MongoDB.

## Getting Started

1. **Clone the repository**:
    ```bash
    git clone https://github.com/varshakodati/registration-form.git
    ```
2. **Install dependencies**:
    ```bash
    cd registration-form
    npm install
    ```
3. **Configure MongoDB**:
    - Create a `.env` file in the root directory.
    - Add your MongoDB connection string as `MONGODB_URI`.

4. **Start the application**:
    ```bash
    npm start
    ```

## Deployment

1. **Create a Render account**.
2. **Initialize a Git repository**:
    ```bash
    git init
    ```
3. **Create a new web service on Render**:
    - Connect your GitHub repository.
    - Set environment variables, including the MongoDB URI.

4. **Deploy the application**:
    - Render will automatically build and deploy upon pushing changes.

5. **Access the deployed app** via the provided URL.

## Result
The registration form securely captures and stores user data in MongoDB, with robust validation to ensure data integrity.

![image](https://github.com/user-attachments/assets/b1fcb308-2483-4f8b-847f-5bed163632d8)

![image](https://github.com/user-attachments/assets/b19a046c-c936-4343-b8d2-9f3675f1a9c1)

## Future Enhancements
- **User Authentication**: Secure user accounts.
- **Profile Management**: Allow users to update profiles.
- **Email Verification**: Enhance security with email verification.
- **Improved UI/UX**: Further polish the user interface.
- **Additional Fields**: Expand the form as needed.

**Author**: Meenu Patel
