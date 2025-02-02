# Imagify

A platform that allows users to generate images from text prompts using AI, manage credits, and purchase more credits via Razorpay.

## Live Site
[Visit the live site](https://imagify-frontend-0eiw.onrender.com/)

## Credentials

- **Email**: `test@gmail.com`
- **Password**: `test123`

## Features
- **Text-to-Image Generation**: Create images from text prompts.
- **User Authentication**: Sign up, log in, and secure access with JWT.
- **Credit System**: Generate images using credits.  
- **Payment Integration (Under Progress)**: Razorpay integration for purchasing credits.
- **Responsive UI**: Smooth, modern design.

## Tech Stack

- **Frontend**: React, Tailwind CSS, Framer Motion
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Image Generation API**: Clipdrop API
- **Payment Gateway**: Razorpay (Integration Under Progress)
- **Authentication**: JWT (JSON Web Tokens)

## Endpoints

### User Routes

- **POST** `/api/user/register` - Register a new user
- **POST** `/api/user/login` - Login an existing user
- **GET** `/api/user/credits` - Get user's credit balance
- **GET** `/api/user/pay-razor` - Start Razorpay payment for credits

### Image Routes

- **POST** `/api/image/generate-image` - Generate image from a text prompt (requires authentication)

