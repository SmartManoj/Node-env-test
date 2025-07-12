# Node Environment Test

A simple npm webpage that uses an environment variable for port configuration.

## Features

- Express.js web server
- Modern responsive UI with gradient design
- Reads `PORT` environment variable
- Fallback to port 3000 if no environment variable is set

## Installation

```bash
npm install
```

## Usage

1. **Set the port environment variable (optional):**
   ```bash
   export PORT=8080
   ```

2. **Start the server:**
   ```bash
   npm start
   ```

3. **Open your browser to:** `http://localhost:3000` (or your custom port)

## API Endpoints

- `GET /` - Serves the main webpage

## Example

```bash
# Set custom port and start server
export PORT=8080; npm start

# Server will run on http://localhost:8080
```

## Project Structure

```
node-env-test/
├── package.json          # Project dependencies
├── server.js            # Express server
├── public/
│   └── index.html       # Frontend webpage
└── README.md           # This file
``` 
