# MERN Authentication Starter

MERN Crash Course | JWT Authentication, Redux Toolkit, Deployment & More

Traversy Media

# [https://github.com/jamesavakian62/reacts_mern_bootstrap_redux_auth/edit/main/readme.md]

This is a starter app for a MERN stack application with authentication. This is for a SPA

![Screenshot 2023-07-23 at 9 10 50 PM](https://github.com/jamesavakian62/reacts_mern_bootstrap_redux_auth/assets/92414210/2606b5f2-765a-4621-b9a1-a8e75f6f2a14)


(Single Page Application) workflow that uses the [Vite](https://vite.dev) Build tool. This authentication workflow is based off of my [MERN Stack From Scratch | eCommerce](https://www.traversymedia.com/mern-stack-from-scratch) course.

<img src="./frontend/public/screen.png" />

It includes the following:

- Backend API with Express & MongoDB
- Routes for auth, logout, register, profile, update profile
- JWT authentication stored in HTTP-only cookie
- Protected routes and endpoints
- Custom middleware to check JSON web token and store in cookie
- Custom error middleware
- React frontend to register, login, logout, view profile, and update profile
- React Bootstrap UI library
- React Toastify notifications

## Usage

- Create a MongoDB database and obtain your `MongoDB URI` - [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)
- Create a PayPal account and obtain your `Client ID` - [PayPal Developer](https://developer.paypal.com/)

### Env Variables

Rename the `.env.example` file to `.env` and add the following

```
NODE_ENV = development
PORT = 5000
MONGO_URI = your mongodb uri
JWT_SECRET = 'abc123'
```

Change the JWT_SECRET to what you want

### Install Dependencies (frontend & backend)

```
npm install
cd frontend
npm install
```

### Run

```

# Run frontend (:3000) & backend (:5000)
npm run dev

# Run backend only
npm run server
```

## Build & Deploy

```
# Create frontend prod build
cd frontend
npm run build
```
