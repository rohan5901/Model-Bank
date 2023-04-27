# Full-Stack International Currency Exchange Web Application

This is a web application built with HTML, CSS, JavaScript, Node.js, Express.js, Mongoose, and MongoDB. The application allows users to make international transactions with different currencies. It automatically does the currency conversion, is dark mode compatible, and users can ask for a loan from the site. Additionally, users can close their accounts, and their passwords are encrypted.

The application uses JSON Web Token (JWT) to handle user authentication and allows users to log in from different devices at the same time.

## Getting Started

To get started with this project, follow the steps below:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/currency-exchange-app.git
   ```
2. Install the project dependencies by running the following command in the root directory of the project:
   ```
   npm install
   ```
3. Create a `.env` file in the root directory of the project and add the following environment variables:
   ```
   MONGO_URI=your-mongodb-uri
   JWT_SECRET=your-jwt-secret
   ```
4. Start the application by running the following command:
   ```
   npm start
   ```
5. The application should now be running on `http://localhost:3000`.

## Features

### Currency Conversion

The application allows users to make international transactions with different currencies. The site automatically does the currency conversion using the latest exchange rates.

### Dark Mode Compatibility

The application has a dark mode feature that users can enable or disable.

### Loan Requests

Users can request a loan from the site only, and the application handles the request and displays the loan details.

### Account Closure

Users can close their accounts if they wish to do so.

### Encrypted Passwords

User passwords are encrypted to ensure maximum security.

### Multi-Device Login

Users can log in from different devices at the same time without any issues.

### JSON Web Token (JWT) Authentication

The application uses JWT to handle user authentication, which is a secure way of handling user login and registration.

## Conclusion

This is a complete and secure full-stack web application that handles international currency transactions, loan requests, and account closure. It is built with the latest web development technologies and follows best practices to ensure maximum security and efficiency.
