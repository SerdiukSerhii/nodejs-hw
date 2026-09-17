# Notes Management API

REST API for managing users and notes, built with Node.js, Express.js, and MongoDB.

## Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)
- bcrypt
- Celebrate
- Nodemailer
- Handlebars
- Cloudinary
- Multer
- cookie-parser
- CORS
- Helmet
- Pino HTTP

## Features

- User registration and authentication
- Notes management and CRUD operations
- JWT-based authentication
- Password reset via email
- Email sending with Nodemailer
- User avatar upload
- Image storage with Cloudinary
- Request validation with Celebrate
- Error handling
- HTTP request logging
- CORS configuration
- Security headers with Helmet

## Deployment

The backend is deployed on Render.

## Environment Variables

Create a `.env` file and configure the following variables:

```env
PORT=
MONGO_URL=
JWT_SECRET=
FRONTEND_DOMAIN=

CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

SMTP_PORT=
SMTP_HOST=
SMTP_USER=
SMTP_PASSWORD=
SMTP_FROM=
```

## Installation

Clone the repository and install the dependencies:

git clone https://github.com/SerdiukSerhii/nodejs-hw.git
cd nodejs-hw
npm install

## Development

Start the development server with Nodemon:

npm run dev
