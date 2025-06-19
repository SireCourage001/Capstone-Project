# Movie Recommendation App - Backend

This is the backend API for the Movie Recommendation App. It is built with Express.js and uses MongoDB for storing user data. JWT is used for secure authentication. A MERN stack

## Features
- User registration and login (JWT auth)
- Secure password hashing with bcrypt
- Protected routes
- TMDB API integration for movie search

## Technologies
- Node.js
- Express.js
- MongoDB + Mongoose
- JSON Web Tokens (JWT)
- dotenv

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/movie-recommendation-app-backend.git
cd movie-app-backend
```

### 2. Install dependencies
```bash
npm install
```

### 3. Create a `.env` file
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
TMDB_API_KEY=your_tmdb_key (if needed in backend)
```

### 4. Run the server
```bash
npm run dev
```

## Deployment
- Deploy to Render
- Set environment variables in Render dashboard
```
MONGO_URI=...
JWT_SECRET=...
TMDB_API_KEY=...
```

## API Endpoints
```
POST /api/auth/register
POST /api/auth/login
GET /api/movies/search?q=...
```
