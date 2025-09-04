# Dockerized Node.js MongoDB Web App

## Description

This is a simple web application built with Node.js and Express, featuring a static frontend and a backend connected to a MongoDB database. The project is containerized using Docker and includes a MongoDB service and a Mongo Express web-based admin interface for database management. All services are managed using Docker Compose for easy local development and testing.

## Features

- Node.js Express server
- Static frontend (HTML/CSS)
- MongoDB database
- Mongo Express admin interface
- Docker Compose setup

## Prerequisites

- [Node.js](https://nodejs.org/)
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/)

## Getting Started

1. Clone the repository:
   ```powershell
   git clone <repository-url>
   cd docker-testapp-main
   ```

2. Install Node.js dependencies:
   ```powershell
   npm install
   ```

3. Start the application:
   ```powershell
   node server.js
   ```

4. Start MongoDB and Mongo Express using Docker Compose:
   ```powershell
   docker-compose -f mongodb.yaml up
   ```

5. Access the app:
   - Web app: [http://localhost:5050](http://localhost:5050)
   - Mongo Express: [http://localhost:8081](http://localhost:8081)

## Project Structure

```
docker-testapp-main/
│
├── server.js
├── package.json
├── mongodb.yaml
├── public/
│   ├── index.html
│   └── style.css
└── README.md
```

## License

This project is licensed under the MIT License.
