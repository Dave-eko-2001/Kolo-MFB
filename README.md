# Kolo Banking App

Kolo is a full-stack banking application designed for stock monitoring, shares purchase, exchange rate switching, and savings management. It features a modern, responsive UI with fluid animations and a secure backend for user authentication.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Setup Instructions](#setup-instructions)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Welcome Page**: A visually appealing landing page with navigation to create an account or log in.
- **Create Account & Login**: User registration and login with a username and 6-digit password.
- **Authentication**: Secure backend validation with MongoDB and bcrypt for password hashing.
- **Feedback Messages**: Displays "Access Granted" (green) or "Access Denied" (red) messages centered on the screen.
- **Fluid Animations**: Smooth transitions and animations using Tailwind CSS and custom keyframes.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Technologies
- **Frontend**: HTML, CSS (Tailwind CSS), JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Dependencies**: bcryptjs (password hashing), cors (cross-origin requests), mongoose (MongoDB ORM)

## Setup Instructions
1. **Prerequisites**:
   - Node.js (v14 or higher)
   - MongoDB (running locally or via a cloud service)
   - Git (for cloning the repository)

2. **Clone the Repository**:
   ```bash
   git clone https://github.com/username/kolo-banking-app.git
   cd kolo-banking-app
