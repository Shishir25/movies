# Movieist Backend API

A backend REST API for a Movie Review Application built with Java, Spring Boot, and MongoDB. The application provides endpoints for retrieving movie information and managing user reviews.

## Features

* Retrieve all movies
* Get movie details by IMDb ID
* Create and store movie reviews
* MongoDB database integration
* RESTful API architecture
* Clean layered backend structure

## Tech Stack

* Java 17
* Spring Boot
* Spring Data MongoDB
* MongoDB Atlas
* Maven
* REST API

## Database

MongoDB is used as the primary database for storing:

* Movie information
* Movie reviews
* IMDb identifiers
* Trailer links and poster information

## Project Structure

```text
src/
├── controller/
├── service/
├── repository/
├── model/
├── config/
└── resources/
```

## API Endpoints

### Get All Movies

```http
GET /api/v1/movies
```

### Get Movie By IMDb ID

```http
GET /api/v1/movies/{imdbId}
```

### Add Review

```http
POST /api/v1/reviews
```

## Installation & Setup

### Clone Repository

```bash
git clone https://github.com/Shishir25/movies.git
cd movies
```

### Configure MongoDB

Add your MongoDB Atlas connection string in:

```properties
spring.data.mongodb.uri=YOUR_MONGODB_CONNECTION_STRING
```

### Run Application

```bash
mvn spring-boot:run
```

The API will be available at:

```text
http://localhost:8080
```

## Skills Demonstrated

* Java Backend Development
* Spring Boot Framework
* MongoDB Database Integration
* REST API Development
* CRUD Operations
* Maven Project Management
* Git & GitHub Version Control

## Future Improvements

* User Authentication with JWT
* Role-Based Authorization
* API Documentation using Swagger
* Docker Deployment
* Unit and Integration Testing

## Author

Shishir Singh

GitHub: https://github.com/Shishir25
