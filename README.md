# MERN Stack Social Media Site

This project is a Social Media Site built using the MERN stack (MongoDB, Express, React, Node.js).

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Setup Instructions](#setup-instructions)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [License](#license)

## Features

- User authentication and authorization
- Profile creation and management
- Posting, liking, and commenting on posts
- Following and unfollowing users
- Real-time notifications
- Search functionality
- Responsive design for both desktop and mobile views

## Tech Stack

- **Frontend**: React, Redux, CSS
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)

## Setup Instructions

### Prerequisites

- Node.js (v14 or above)
- npm or yarn
- MongoDB

### Installation

1. **Clone the repository:**

    ```sh
    git clone https://github.com/shreya-ghimire/Social-media.git
    cd mern-social-media
    ```

2. **Backend Setup:**

    - Navigate to the backend directory:
    
      ```sh
      cd backend
      ```
    
    - Install backend dependencies:
    
      ```sh
      npm install
      ```
    
    - Create a `.env` file in the backend directory and add your database configuration and other environment variables:
    
      ```
      MONGO_URI=your_mongodb_uri
      JWT_SECRET=your_jwt_secret
      PORT=your_port
      ```
    
    - Start the backend server:
    
      ```sh
      npm start
      ```

3. **Frontend Setup:**

    - Navigate to the frontend directory:
    
      ```sh
      cd ../frontend
      ```
    
    - Install frontend dependencies:
    
      ```sh
      npm install
      ```
    
    - Create a `.env` file in the frontend directory and add your API endpoint configuration:
    
      ```
      REACT_APP_API_URL=http://localhost:your_backend_port/api
      ```
    
    - Start the frontend development server:
    
      ```sh
      npm start
      ```

    The application should now be running and accessible at `http://localhost:3000`.

## Project Structure

