# Jobs API

Welcome to the Jobs API! This API allows users to register, login, create, update, delete jobs, and get information about jobs.

## Getting Started

To get started with the API, follow these steps:

1. Clone this repository.
2. Install dependencies: `npm install`
3. Set up your environment variables:
   - Create a `.env` file.
   - MONGO_URI, JWT_SECRET, JWT_LIFETIME
4. Start the server: `npm start`
5. Explore the API using the provided Swagger UI documentation.

## Documentation

For detailed documentation on how to use the API, please refer to the Swagger UI documentation:

[Jobs API Documentation](https://the-jobs-api-15608e92fff8.herokuapp.com/)

## Features

- User Authentication: Register and login to manage jobs.
- CRUD Operations: Create, Read, Update, and Delete jobs.
- Secure Endpoints: Protected endpoints require authentication.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Swagger UI
- JWT for authentication

## API Endpoints

- POST /api/v1/auth/register: Register a new user.
- POST /api/v1/auth/login: Login an existing user.
- POST /api/v1/jobs: Create a new job.
- GET /api/v1/jobs: Get all jobs.
- GET /api/v1/jobs/{id}: Get a single job by ID.
- PATCH /api/v1/jobs/{id}: Update a job by ID.
- DELETE /api/v1/jobs/{id}: Delete a job by ID.

## License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.
