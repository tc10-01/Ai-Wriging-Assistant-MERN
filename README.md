# AI Writing Assistant - MERN Stack Application

A modern web application that helps users improve their writing using AI technology. Built with the MERN stack (MongoDB, Express.js, React, Node.js) and featuring a beautiful, responsive UI powered by Tailwind CSS.

## Features

- 🤖 AI-powered writing assistance
- 🔐 Secure authentication using Privy
- 🎨 Modern, responsive UI with Tailwind CSS
- ⚡ Fast and efficient performance with Vite
- 🔄 Real-time updates and feedback

## Tech Stack

### Frontend
- React.js
- Tailwind CSS
- Vite
- React Router DOM
- Privy Authentication
- Axios for API calls

### Backend
- Node.js
- Express.js
- MongoDB
- Axios
- CORS
- dotenv for environment variables

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB

### Installation

1. Clone the repository
```bash
git clone https://github.com/tc10-01/Ai-Wriging-Assistant-MERN.git
cd Ai-Wriging-Assistant-MERN
```

2. Install backend dependencies
```bash
cd server
npm install
```

3. Install frontend dependencies
```bash
cd ../client
npm install
```

4. Set up environment variables
- Create a `.env` file in the server directory
- Add your MongoDB connection string and other necessary environment variables

### Running the Application

1. Start the backend server
```bash
cd server
npm start
```

2. Start the frontend development server
```bash
cd client
npm run dev
```

The application will be available at `http://localhost:5173`

## Project Structure

```
Ai-Wriging-Assistant-MERN/
├── client/                 # Frontend React application
│   ├── src/               # Source files
│   ├── public/            # Static files
│   └── package.json       # Frontend dependencies
├── server/                # Backend Node.js application
│   ├── routes/           # API routes
│   ├── app.js            # Main server file
│   └── package.json      # Backend dependencies
└── README.md             # Project documentation
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the ISC License - see the LICENSE file for details.

## Acknowledgments

- [Privy](https://www.privy.io/) for authentication
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [Vite](https://vitejs.dev/) for the build tool
