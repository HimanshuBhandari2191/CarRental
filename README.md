# Car Rental Application

A full-stack Car Rental platform built with the MERN stack, featuring a responsive frontend, a scalable backend, and secure authentication.

## 🚀 Live Demo

Check out the live application here: **[https://car-rental-alpha-black.vercel.app/](https://car-rental-alpha-black.vercel.app/)**

## 🛠 Tech Stack

### Frontend
- **React** (via Vite)
- **Tailwind CSS** - For styling
- **Framer Motion** - For animations
- **React Router DOM** - For navigation
- **Axios** - For API requests

### Backend
- **Node.js & Express** - REST API architecture
- **MongoDB** - Database
- **JWT** - Authentication & Authorization
- **ImageKit** - Cloud image storage and optimization

##  Features

- **User Authentication**: Secure signup and login using JWT.
- **Browse Cars**: View available cars for rent.
- **Image Management**: Car images handled via ImageKit.

- **Responsive Design**: Mobile-friendly UI built with Tailwind.

## 🔧 Setup & Installation

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd CarRental
   ```

2. **Configure Environment Variables**
   Create a `.env` file in the `server` directory and add the following variables:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   IMAGEKIT_PUBLIC_KEY=your_public_key
   IMAGEKIT_PRIVATE_KEY=your_private_key
   IMAGEKIT_URL_ENDPOINT=your_url_endpoint
   ```

3. **Backend Setup**
   Navigate to the server directory, install dependencies, and start the server:
```bash
cd server
npm install
npm run start
```

4. **Frontend Setup**
   Navigate to the client directory, install dependencies, and start the client:
```bash
cd client
npm install
npm run dev
```

## 📂 Project Structure

- **client/**: React frontend application.
- **server/**: Node.js/Express backend API.

## 📝 License
This project is open source.
