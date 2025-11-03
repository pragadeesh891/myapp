# Express.js Docker Application

A simple Express.js application containerized with Docker.

## Features
- Express.js web server
- Docker containerization
- Simple "Hello World" endpoint

## Getting Started

### Prerequisites
- Node.js
- Docker

### Running Locally
```bash
npm install
npm start
```

### Running with Docker
```bash
docker build -t myapp .
docker run -p 3000:3000 myapp
```

Visit `http://localhost:3000` to see the application running.