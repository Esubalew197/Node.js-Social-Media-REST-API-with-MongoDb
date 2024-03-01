# Node.js Social Media REST API

This project is a social media REST API built using Node.js, Express, and MongoDB. It provides endpoints for user authentication, creating and managing posts, following other users, and more.

## Features
- User registration and login
- Create, edit, and delete posts
- Like and comment on posts
- Follow and unfollow other users
- User profile management
- Token-based authentication using JWT
- MongoDB for data storage

## Installation
1. Clone this repository:
git clone https://github.com/Esubalew197/Node.js-Social-Media-REST-API-with-MongoDb.git

2. Install dependencies:

3. Set up your environment variables:
- Create a `.env` file in the root directory.
- Add the following variables:
  ```
  PORT=3000
  MONGO_URL = MONGODB_URI=your-mongodb-connection-string
  ```

4. Start the server:
npm start

## API Endpoints
- `POST /api/auth/register`: Register a new user
- `POST /api/auth/login`: Log in an existing user
- `PUT /api//api/users/:id`: Update a user
- `DELETE /api//api/users/:id`: Delete a user
- `DELETE /api//api/users/:id`: GET a user
- `PUT /api//api/users/:id/follow`: Follow a user
- `PUT /api//api/users/:id/unfollow`: Unfollow a user
- `POST /api/posts`: Create a new post
- `PUT /api/posts/:id`: Update a post
- `DELETE /api/posts/:id`: Delete a post
- `GET /api/posts/timeline/all`: Get all posts
- `PUT /api/posts/:id/like`: Like and dislike a post

## Contributing
Contributions are welcome! Please feel free to open issues or submit pull requests.
