# My Express App

This is a simple Node.js Express application that demonstrates how to set up an Express server and containerize it using Docker.

## Project Structure

```
my-express-app
├── src
│   └── app.js
├── package.json
├── Dockerfile
└── README.md
```

## Getting Started

### Prerequisites

- Node.js
- Docker

### Installation

1. Clone the repository:

   ```
   git clone <repository-url>
   cd my-express-app
   ```

2. Install dependencies:

   ```
   npm install
   ```

### Running the Application

You can run the application locally using the following command:

```
node src/app.js
```

### Running with Docker

To build and run the application in a Docker container, follow these steps:

1. Build the Docker image:

   ```
   docker build -t my-express-app .
   ```

2. Run the Docker container:

   ```
   docker run -p 3000:3000 my-express-app
   ```

The application will be accessible at `http://localhost:3000`.

### License

This project is licensed under the MIT License.