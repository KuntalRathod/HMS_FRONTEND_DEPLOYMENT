# Hospital Management System :- A robust MERN-based system for hospitals.

Features authentication & authorization, working with multiple json web tokens, dual frontends (user and admin)

## Features
### Authentication & Authorization
* Standard authentication

### Patient Appointment Management
* The patient can easily send appointment to their choice of doctors and their choice of related departments.

### Handling the two tokens in same time Patient token and admin token in cookies
  
### Admin Dashboard
* Access and view detailed information about Patient appointments.
* Admin can register a new doctor with all important information about doctor.
* Admin can view the all registered doctors.
* Admin can Add a new Admin.
* Admin can view all the messages send by user or patients. 

## Technologies Used

### Client Side 
* **React** :- for building the website.
* **React-Router-Dom** :- for navigating between different pages on the website.
* **React-Context-Api** :- for manage website's data and state
* **React-icons** :- for adds icons to the website for visual appeal.
* **React-toastify** :- for shows pop-up messages on the website.

### Server Side
* **Node.js & Express.js** :- for the core of the backend development.
* **MongoDB & Mongoose** :- database management for storing user data. 
* **JWT** :- for Ensuring secure user authentication.
* **Bcrypt** :- for password hashing.
* **Express-fileupload & Cloudinary**: for Handling file uploads and cloud storage. 
* **Cookie-parser , Cors and Many More**.

## Configuration 
***Configure your application using the following environment variables:***

### Client Side
***https://hms-backend-deployment-y3o9.onrender.com*** = set your backend Server url instead of this url add like http://localhost:4000/ 

### Server side -> config.env
* ***FRONTEND_URL*** = set your frontend url.
* ***PORT*** = port number.
* ***MONGO_URI*** = MongoDB connection URI.
* ***JWT_SECRET_KEY*** =  Set to a secure string for generating json web tokens.
* ***JWT_EXPIRES*** = token expiry.
* ***DASHBOARD_URL*** = set  your frontend url.
* ***COOKIE_EXPIRE*** = cookie expiry. 
* ***CLOUDINARY_CLOUD_NAME*** = Set to your Cloudinary cloud name.
* ***CLOUDINARY_API_KEY*** = Set to your Cloudinary API key.
* ***CLOUDINARY_API_SECRET*** = Set to your Cloudinary API secret.

## Installation
* Clone the repository 
### Server side 
* change directory to **backend** folder
* Install dependencies using **npm install**
* Set up environment variables **.env**
* Run the application using **npm run start** 
### Client side
* change directory to **frontend** folder
* Install dependencies using **npm install**
* Run the application using **npm run dev**
* ### Client side
* change directory to **dashboard** folder
* Install dependencies using **npm install**
* Run the application using **npm run dev** 

## Usage

* Access the application through the provided URL
* Use the provided authentication methods to log in
* You(Patient) can send appointment to your doctor and you can choice your doctor and their department 
* Admin can see all patient appointment details & messages and register new doctor and register new admin and all action perform via the admin dashboard.

***Made by 😎❤️ [Kuntal](https://www.linkedin.com/in/kuntal-rathod-b5ba5a239/)*** click and visit.
