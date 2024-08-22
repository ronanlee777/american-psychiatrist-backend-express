# American Psychiatrists (React + Vite + Tailwind CSS)

## Overview

This is the backend server for the American Psychiatrists website, built using Express.js and PostgreSQL. It provides a RESTful API for handling user authentication, psychiatrist profiles, and search functionality.

## Introduction

The American Psychiatrists Backend is a robust and scalable server-side application that powers the American Psychiatrists website. It is developed using Node.js and Express.js, with PostgreSQL as the database management system. This project is developed by Dane Manji.
The website is hosted at [www.americanpsychiatrists.com](https://americanpsychiatrists.com/).

## Skill Sets

- Node.js
- Express.js
- PostgreSQL
- JWT (JSON Web Tokens) for authentication
- Bcrypt for password hashing

## Prerequiries

Before using this project, ensure that you have the following installed on your computer: 
- Node 16.20 (I used the older version because it will be deployed on bluehost, which has an operating system of centos 7 and cause of this, 
  requires Node  less than version 18.)
- TypeScript
- Vite

## Installation & Usage

To install the American Psychiatrists Project, follow these steps:

1. Clone the repository from GitHub.
2. Navigate to the project directory: cd `american-psychiatrists-backend`
3. Install the required React modules using `npm install`
4. Create a PostgreSQL database and update the database connection details in the config/dbConfig.js file.
5. Start the React server using the command `npm start`

## Environment Variables
The following environment variables are required for the application to run:

- /config/db/dbConfig.js

host: The hostname of the PostgreSQL database.
port: The port number of the PostgreSQL database.
user: The username for the PostgreSQL database.
password: The password for the PostgreSQL database.
database: The name of the PostgreSQL database.

- /config/env/
secret: The secret key used for JSON Web Token (JWT) authentication.

## Contributing
Contributions to the American Psychiatrists Backend are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Conclusion

The American Psychiatrists Backend provides a robust and scalable server-side solution for the American Psychiatrists website. It offers a secure and efficient way to manage user authentication, psychiatrist profiles, and search functionality. For any inquiries or support, please contact the developer at ronanlee777@gmail.com.
