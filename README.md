# Jobify - MERN Stack Job Board

![https://github.com/Louai-Zokerburg/mern-stack-jobify/blob/main/cover.png?raw=true](https://github.com/Louai-Zokerburg/mern-stack-jobify/blob/main/cover.png?raw=true)

## **Live Demo**

Check out the live demo of the app [here](https://jobfy-mern-app.onrender.com)

## **Description**

Jobify is a full-stack MERN (MongoDB, Express, React, Node.js) web application that empowers users to manage job-related activities efficiently. The app provides a feature-rich interface with secure authentication, comprehensive job management, and user profile customization.

## **Tech Stack**

- **Frontend:**
    - React
    - Styled Components
    - React Query
    - React Context
    - Recharts.js
    - Axios
- **Backend:**
    - Express
    - Node.js
    - MongoDB (Cloud Database)
    - Cloudinary (Image Storage)
    - JSON Web Token (JWT) for authentication

## **Features**

- 🌐 **User Authentication:**
    - Securely sign up or log in to access personalized features.
- 🕵️ **Job Browsing:**
    - Explore a vast array of available jobs with detailed information.
- ➕ **Add New Jobs:**
    - Registered users can contribute to the job board by adding new job listings.
- ❌ **Delete Jobs:**
    - Remove job listings that are no longer relevant or required.
- 🔄 **Update Jobs:**
    - Modify job details or requirements for existing listings.
- 🔍 **Search Jobs:**
    - Easily search for specific jobs based on keywords or criteria.
- 🎯 **Filter Jobs:**
    - Utilize filtering options to narrow down job listings based on various parameters.
- 🔐 **Login & Signup:**
    - A secure authentication system for user accounts.
- 🖼️ **Add Profile Picture:**
    - Personalize your profile by adding a custom profile picture.

## **How to Install**

1. **Clone Repository:**
    
    ```bash
    git clone https://github.com/Louai-Zokerburg/mern-stack-jobify.git
    ```
    
2. **Install Dependencies For the server:**
    
    ```bash
    cd mern-stack-jobify
    npm install
    ```
    
3. **Install Dependencies For the client:**
    
    ```bash
    cd client
    npm install
    ```
    
4. **Configure Environment Variables:**
Create a **`.env`** file in the root of the project with the following variables:
    
    ```makefile
    MONGO_URL=
    PORT=5100
    NODE_ENV=development
    
    CLOUD_NAME=
    CLOUD_API_KEY=
    CLOUD_API_SECRET=
    
    JWT_SECRET=
    JWT_EXPIRES_IN=
    ```
    
5. **Run the Application:**
    
    ```bash
    npm run server
    ```
    

## **Usage**

1. **User Registration/Login:**
    - Open the app and sign up or log in using your credentials.
2. **Job Browsing:**
    - Explore available jobs on the main dashboard.
3. **Add New Jobs:**
    - If logged in, contribute to the job board by adding new job listings.
4. **Delete Jobs:**
    - Remove job listings that are no longer relevant.
5. **Update Jobs:**
    - Modify job details or requirements for existing listings.
6. **Search Jobs:**
    - Use the search feature to find specific jobs based on keywords.
7. **Filter Jobs:**
    - Utilize filtering options to narrow down job listings based on various parameters.
8. **Login & Signup:**
    - Securely manage your account through the authentication system.
9. **Add Profile Picture:**
    - Personalize your user profile by adding a custom profile picture.