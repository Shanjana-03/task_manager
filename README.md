# Task Manager Application

A modern full-stack task management application built with the MERN stack (MongoDB, Express.js, React, Node.js). This application provides an intuitive interface for users to create, organize, and track their tasks efficiently. The frontend is built with React and powered by Vite for optimal performance, while the backend utilizes Express.js with MongoDB for robust data persistence. The application features a responsive design, making it accessible across various devices.

## Project Structure

```
├── frontend/          # React frontend (Vite)
│   ├── src/          # Source files
│   ├── public/       # Static files
│   └── index.html    # Entry HTML file
└── backend/          # Node.js backend
    └── server.js     # Express server
```

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- MongoDB (Make sure MongoDB server is running locally)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Shanjana-03/task.git
cd task-manager-app
```

2. Install frontend dependencies:
```bash
cd frontend
npm install
```

3. Install backend dependencies:
```bash
cd ../backend
npm install
```

### Running the Application

1. Start the backend server:
```bash
cd backend
npm start
```

2. In a new terminal, start the frontend development server:
```bash
cd frontend
npm run dev
```

The application should now be running at `http://localhost:5173` (frontend) and the backend API at `http://localhost:3000`.

## Features

- Task management with CRUD operations
- Modern and responsive user interface
- RESTful API backend

## Tech Stack

### Frontend
- React
- Vite (build tool)
- Modern CSS

### Backend
- Node.js
- Express.js
- MongoDB (Database)
- Mongoose (ODM)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

[Shanjana-03](https://github.com/Shanjana-03)
