# Pet E-commerce Website

## Overview
This project is a full-fledged pet e-commerce website built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows admins to post new ads for selling pets with detailed information such as breed, price, age, etc. Users can browse the ads and create inquiries about the pets they are interested in.

## Features
- **Admin Panel**: Admins can log in and post new ads with detailed information about pets.
- **User Interface**: Users can browse through the list of available pets and view detailed information.
- **Inquiry System**: Users can create inquiries about specific pets they are interested in.
- **Authentication**: Secure login for both admins and users.
- **Responsive Design**: The website is responsive and works well on both desktop and mobile devices.

## Tech Stack
- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Styling**: CSS, Bootstrap

## Installation

### Prerequisites
- Node.js
- MongoDB

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/anshika1307-code/Production-PetEcommerce.git
   ```
2. **Clone the frontend repo**
   ```bash
     git clone https://github.com/anshika1307-code/PetAdoreHub-Frontend.git
   ```
3. Navigate to the project directory

```bash
cd Production-PetEcommerce
Install server dependencies
```
```bash
cd server
npm install
Install client dependencies
```
```bash
cd ../client
npm install
Setup environment variables
```
Create a .env file in the server directory and add the following:

```makefile
PORT=
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Run the server
```
```bash
cd ../server
npm start
```

## Demo

You can access the live application [here](https://petecommerce.onrender.com).
