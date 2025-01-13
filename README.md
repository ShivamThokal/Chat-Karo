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
- **frontend/**: Contains the client-side code, built with React and Vite.
  - **Key Dependencies:**
    - `axios`: For API requests.
    - `react-router-dom`: For routing.
    - `zustand`: For state management.
    - `tailwindcss`: For styling.
    - `socket.io-client`: For real-time communication.
  - **Scripts:**
    - `dev`: Runs the development server.
    - `build`: Builds the frontend application.
    - `lint`: Runs ESLint for code quality checks.
    - `preview`: Previews the production build.

- **backend/**: Contains the server-side code, built with Express.
  - **Key Dependencies:**
    - `express`: For creating the server.
    - `mongoose`: For database management.
    - `jsonwebtoken`: For authentication.
    - `bcrypt`: For password hashing.
    - `socket.io`: For real-time communication.
  - **Scripts:**
    - `dev`: Starts the backend server in development mode with `nodemon`.
    - `start`: Starts the backend server in production mode.

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

## License
This project is licensed under the ISC License.

## Author
[Your Name]

---

Feel free to customize this README file to better suit your project specifics!

