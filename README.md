
# E-Commerce Website

## Overview
This is an E-Commerce website built with a Node.js backend and a React frontend. The application allows users to browse products, manage their cart, place orders, and make payments. It features user authentication and integrates with Cloudinary for image uploads.

## Features
- **User Authentication**: Secure login and registration.
- **Product Listing**: Users can view available products with details.
- **Cart Management**: Users can add or remove products from their cart.
- **Order Tracking**: Users can track their orders.
- **Payment Integration**: Secure payment processing.
- **Image Uploads**: Utilizes Cloudinary for storing product images.

## Technologies Used
- **Backend**:
  - Node.js
  - Express.js
  - MongoDB (with Mongoose)
  - JWT for authentication
  - Cloudinary for image storage
  - Multer for handling file uploads

- **Frontend**:
  - React.js
  - Redux Toolkit for state management
  - Styled Components for styling
  - Ant Design for UI components

## Installation Instructions

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local or cloud instance)
- Cloudinary account

### Backend Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd E-commerce/Backend

2. Install dependencies:
  npm install

3. Create a .env file in the Backend directory and add your environment variables
  DB_URL=<your_mongodb_connection_string>
  CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
  CLOUDINARY_API_KEY=<your_cloudinary_api_key>
  CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
  JWT_SECRET_BACKEND=<your_jwt_secret>
  PORT=3000

4. Start the server:
  npm start

# Frontend Setup

1. Navigate to the frontend directory:
   cd ../Frontend  # Adjust this path based on your structure

2. Install dependencies:
   npm install

3. Start the frontend application:
    npm start

# Usage
Once both the backend and frontend are running, you can access the website at http://localhost:3000 (or whichever port your frontend is running on).

API Endpoints
  Products: /api/products
  User: /api/user
  Cart: /api/cart
  Order: /api/order
  Payment: /api/payment
