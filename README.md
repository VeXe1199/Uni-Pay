# University Payment App

The University Payment App is designed to help students manage their financial activities efficiently and securely. The app provides functionalities like user registration, secure login, transaction processing, monthly credit allocation, and real-time notifications. It also supports multi-platform compatibility and includes robust security measures to protect user data.

## Table of Contents
- [Features](#features)
- [Requirements](#requirements)
- [Tools and Technologies](#tools-and-technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Registration**: Allow students and entities to create an account.
- **Authentication**: Secure login system for registered users.
- **Transaction Processing**: Secure initiation and completion of transactions.
- **Reporting and Analytics**: Generate reports on transactions and account activities.
- **User Feedback**: Mechanism for users to submit opinions and suggestions.
- **Customer Support**: Integrated support system for user queries and issues.
- **Multi-Platform Compatibility**: Works seamlessly on both Android and iOS platforms.
- **Database Management**: Efficient and secure storage of user data and transaction records using MongoDB through Mongoose ODM.

## Requirements
| Requirement ID | Description |
|----------------|-------------|
| REQ-01 | Sign-in and Sign-up: Allow users to register and log in to their accounts. |
| REQ-02 | Send Money: Enable users to send money securely to others. |
| REQ-03 | Check Balance: Allow users to check their account balance. |
| REQ-04 | Transaction History: Provide users with a history of their transactions. |
| REQ-05 | Pay to Daily Repeat Transaction: Implement a feature to repeat daily transactions easily. |
| REQ-06 | Admin Section: Include an admin section for managing users and transactions. |
| REQ-07 | QR Scanning and Payment: Support QR code scanning for payments. |
| REQ-08 | Payment through Unique Transaction ID: Allow payments to be made using unique transaction IDs. |


## Tools and Technologies

### Backend Technologies
- **Express**: HTTP server for web applications.
- **Mongoose ODM**: Connects Express to MongoDB, simplifying MongoDB data interactions.
- **Zod**: TypeScript-first schema and validation library, ensuring input data conformity.

### Frontend Technologies
- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for styling.

### Dependencies
- **cors**: Handles cross-origin resource sharing.
- **body-parser**: Middleware for parsing HTTP request bodies.
- **jwt**: Manages JSON Web Tokens for authentication.
