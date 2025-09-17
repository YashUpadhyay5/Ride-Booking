# Ride Booking Project

This repository contains the source code for the Ride Cab application, which consists of a backend (Node.js/Express) and a frontend (React/Vite).

## Project Structure

```
Backend/      # Node.js backend server
frontend/     # React frontend application
```

### Backend
- RESTful API for user, captain, and ride management
- Socket.io for real-time communication
- MongoDB database integration
- Authentication and authorization middleware

### Frontend
- React app bootstrapped with Vite
- Tailwind CSS for styling
- Components for ride booking, live tracking, and user/captain flows

## Getting Started

### Prerequisites
- Node.js (v16+ recommended)
- npm or yarn
- MongoDB instance (local or cloud)

### Backend Setup
1. Navigate to the backend folder:
   ```sh
   cd Backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Configure environment variables (e.g., MongoDB URI, JWT secret).
4. Start the backend server:
   ```sh
   npm start
   ```

### Frontend Setup
1. Navigate to the frontend folder:
   ```sh
   cd frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the frontend development server:
   ```sh
   npm run dev
   ```

## Features
- User and Captain authentication
- Ride booking and management
- Real-time ride tracking
- Responsive UI

## Folder Details
- `Backend/controllers/` - API controllers
- `Backend/models/` - Mongoose models
- `Backend/routes/` - Express routes
- `Backend/services/` - Business logic
- `frontend/src/components/` - React components
- `frontend/src/pages/` - Page components
- `frontend/src/context/` - React context providers

## License
MIT
