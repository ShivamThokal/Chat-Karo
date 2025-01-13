# ChatApp

## Description
ChatApp is a full-stack chat application designed to provide seamless communication between users. This project consists of a `frontend` and a `backend` folder, each responsible for their respective functionalities. The project uses Node.js and Express for the backend, and React with Vite for the frontend.

## Features
- **Real-time messaging**
- **User authentication**
- **Responsive user interface**
- **Secure communication**

## Prerequisites
Ensure you have the following installed:
- Node.js (v16 or higher)
- npm (Node Package Manager)

## Installation and Setup
To set up the project locally, follow these steps:

### Clone the Repository
```bash
git clone https://github.com/ShivamThokal/chat-karo.git
cd chatapp
```

### Setup .env File
Create a `.env` file in the `backend` directory with the following configuration:
```env
MONGODB_URI=...
PORT=5002
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Install Dependencies
Run the following command to install dependencies for both the backend and frontend:
```bash
npm run build
```

### Build the App
To build the application, run:
```shell
npm run build
```

### Start the App
To start the application in production mode, run:
```shell
npm start
```

## Folder Structure
- **backend/**: Contains the server-side code, built with Express.
  - **src/**:
    - **controllers/**: Contains controller logic for handling requests.
    - **lib/**: Contains helper functions or utility modules.
    - **middleware/**: Middleware for request processing (e.g., authentication).
    - **models/**: Database schemas and models.
    - **routes/**: API routes for the application.
    - **seeds/**: Data seeding files for initializing the database.

- **frontend/**: Contains the client-side code, built with React and Vite.
  - **dist/**: The production build of the frontend application.
    - **assets/**: Compiled static assets.
  - **public/**: Public static files like `index.html`.
  - **src/**:
    - **assets/**: Images and other static resources used in the application.
    - **components/**: Reusable React components.
      - **skeletons/**: Skeleton loaders for components.
    - **constants/**: Application constants and configuration files.
    - **lib/**: Helper functions or utility modules for the frontend.
    - **pages/**: React components representing individual pages.
    - **store/**: State management setup (e.g., Zustand store).



## Scripts
- **`npm run build`**: Installs dependencies for both the backend and frontend, and builds the frontend application.
- **`npm run start`**: Starts the backend server.

## Development
To run the application in development mode:
1. Start the backend server:
   ```bash
   npm run dev --prefix backend
   ```
2. Start the frontend development server:
   ```bash
   npm run dev --prefix frontend
   ```


