# NetflixClone

This project is a Netflix Clone built using the MERN stack. It includes a frontend created with React and a backend using Node.js, Express, and MongoDB.

## Features

- Browse Movies and TV Shows: Users can browse a wide range of movies and TV shows.
- Search Functionality: Users can search for their favorite movies and TV shows.
- User Authentication: Secure login and registration using Firebase.
- Real-time Notifications: Users receive real-time updates using `react-hot-toast`.
- Comprehensive Movie Data: Integrated with IMDb and custom RESTful APIs for fetching movie data.
  
## Tech Stack

### Frontend
- React
- Redux Toolkit
- React Router DOM
- Axios
- Tailwind CSS
- React Icons
- React Hot Toast

### Backend
- Node.js
- Express
- Mongoose
- JWT for authentication
- Bcrypt for password hashing
- Cors
- Dotenv
- Cookie-parser

## Installation

### Frontend

1. Clone the repository:
    git clone https://github.com/Namrathakaki987/netflix-ui.git
    cd netflix-ui
    
2. Install the dependencies:
    npm install
    
3. Start the development server:
    npm start
    

### Backend

1. Clone the repository:
    git clone https://github.com/Namrathakaki987/backend.git
    cd backend
  

2. Install the dependencies:
    npm install
    

3. Create a `.env` file in the root directory and add the following environment variables:
    MONGO_URI=your_mongo_db_uri
    JWT_SECRET=your_jwt_secret

4. Start the development server
    npm run dev


## Usage

- Access the frontend at `http://localhost:3000`
- The backend runs on `http://localhost:5000`

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
