# MERN Chat App
![mern-ui](./Capture.png)

This is a full-stack chat application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). Users can sign up, log in, and chat in real-time with other users.

## Features

- User authentication: Sign up, log in, log out.
- Real-time messaging using WebSocket with Socket.io.
- Responsive design.
- User-friendly interface.

## Technologies Used

- **Frontend:**
  - React.js
  - React Router DOM
  - React Icons
  - Zustand (for state management)
  - React Hot Toast (for toast notifications)

- **Backend:**
  - Express.js
  - MongoDB with Mongoose (for database)
  - JSON Web Tokens (JWT) for authentication
  - Socket.io (for real-time communication)
  - Bcryptjs (for password hashing)
  - Cookie-parser (for parsing cookies)
  - Dotenv (for environment variables)
  - Nodemon (for automatic server restart)

- **Build Tools:**
  - Vite (for frontend build)
  - Tailwind CSS (for styling)
  - DaisyUI (for additional Tailwind CSS components)
  - PostCSS and Autoprefixer (for CSS processing)

- **Development Tools:**
  - ESLint (for linting)
  - eslint-plugin-react and eslint-plugin-react-hooks (for React linting)
  - eslint-plugin-react-refresh (for React refresh linting)
  - @types/react and @types/react-dom (for TypeScript support)
  - @vitejs/plugin-react (for React support in Vite)

## Installation

1. Clone this repository.
2. Navigate to the project directory.
3. Install dependencies using the following command:

```bash
npm build
```

4. Create a .env file in the root directory and add the environment variables:

```bash
MONGODB_URI=
JWT_SECRET=
PORT=
NODE_ENV=
```

5. Start the development server:

```bash
npm start
```
