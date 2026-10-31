# Lab 1: Node.js and Express Server

A simple Express.js REST API server built for Lab 1.

## Features & Endpoints

- **`GET /`** - Returns a welcome message: `"Welcome to my server!"`
- **`GET /about`** - Returns student details in JSON format (`name` and `section`)
- **`GET /time`** - Returns current date and time string
- **`404 Handler`** - Handles undefined routes with `"404 - Page not found"`

## Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm

### Installation
```bash
npm install
```

### Running the Server
```bash
npm start
```
or
```bash
node server.js
```
The server will start on `http://localhost:3000`.
