# Student CRUD System

## Overview

The **Student CRUD System** is a web application designed to manage student records efficiently. It provides features for user registration, login, and CRUD (Create, Read, Update, Delete) operations on student data. This application leverages a modern tech stack to deliver a secure and user-friendly experience.

## Live Demo

Access the live application here: [Student CRUD System](https://ultatel-task-frontend.vercel.app/)

## Features

- **User Authentication**: Secure user registration and login with hashed passwords. Users must confirm their email before logging in.
- **Students Management**: Full CRUD operations for managing student data.
- **Responsive Design**: Optimized for various devices.
- **Email Confirmation**: Requires email confirmation for new accounts. Includes functionality to resend confirmation emails.

## Tech Stack

### Frontend

- **Angular**: For building a dynamic and responsive UI.
- **Bootstrap**: To style the application.
- **ng-bootstrap**: Angular integration with Bootstrap.
- **ng-select**: For enhanced select boxes.
- **sweetalert2**: For beautiful alerts and notifications.
- **Datepicker**: For selecting dates in forms.

### Backend

- **NestJS**: For creating a robust and scalable RESTful API.
- **RESTful API**: Design pattern for the backend services.
- **Swagger**: Integrated for API documentation and testing.
- **ORM / Repository Pattern**: For database interactions.

### Database

- **MySQL**: Relational database management system used for storing data.
- **Database Host**: [freesqldatabase](https://www.freesqldatabase.com/)

## Setup Instructions

### Prerequisites

- Node.js (version 16.x or later)
- Angular CLI (version 15.x or later)
- MySQL Server
- NestJS CLI (version 9.x or later)

### Backend Setup

1. **Clone the Repository**

```bash
   git clone https://github.com/FatmaElzahraaAhmed/UltatelTask
   cd student-crud-backend
   ```

2. **Install Dependencies**
 ```bash
   npm install --force
```
3. **Configure Environment Variables**

   Create a `.env` file in the `backend` directory with the following content:
 ```bash
   DATABASE_HOST=your_database_host
   DATABASE_PORT=3306
   DATABASE_USER=your_database_user
   DATABASE_PASSWORD=your_database_password
   DATABASE_NAME=ultateltask

   JWT_SECRET=your_jwt_secret
   MAIL_HOST=smtp.yourmailhost.com
   MAIL_PORT=587
   MAIL_USER=yourmailuser
   MAIL_PASSWORD=yourmailpassword
```
4. **Start the Backend Server**
 ```bash
   npm run start:dev

   The backend server will be available at `http://localhost:3000`.
```
### Frontend Setup

1. **Navigate to the Frontend Directory**
 ```bash
   cd ../student-crud-app
```
2. **Install Dependencies**
 ```bash
   npm install --force
```

3. **Run the Angular Application**
 ```bash
   ng serve --open

   The frontend will be available at `http://localhost:4200`.
```
### Database Setup

Ensure that your MySQL server is running and you have created a database (`ultateltask`) as specified in the `.env` file for the backend.

### Deployment

- **Backend**: Deployed using Railway. Ensure your environment variables are set in the Railway project settings.
- **Frontend**: Deployed using Vercel.

## Usage

### Registration

1. Navigate to the registration page.
2. Enter your email and password.
3. Click on the confirmation link sent to your email.

### Login

1. Navigate to the login page.
2. Enter your email and password.

### Managing Students

1. Once logged in, you can create, edit, or delete student records via the UI.

## API Documentation

Swagger is integrated for API documentation and can be accessed at [Swagger Documentation](https://ultateltask-backend-production.up.railway.app/swagger) when the backend server is running.

## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.


## Contact

For any questions or suggestions, please contact us at [fatmaahmed2272001@gmail.com](mailto:fatmaahmed2272001@gmail.com).
