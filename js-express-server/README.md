# js-express-server

This is a simple Express server project that listens on port 8001. It is set up to use nodemon for automatic code reloading during development.

## Project Structure

```
js-express-server
├── src
│   └── index.js          # Entry point of the application
├── .gitignore            # Specifies files to ignore in Git
├── Dockerfile            # Instructions to build the Docker image
├── package.json          # Configuration file for npm
├── yarn.lock             # Locks the versions of dependencies
└── README.md             # Documentation for the project
```

## Getting Started

To get started with this project, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd js-express-server
   ```

2. **Install dependencies**:
   ```bash
   yarn install
   ```

3. **Run the server**:
   ```bash
   yarn start
   ```

The server will start and listen on port 8001.

## Docker

To build and run the Docker container, use the following commands:

1. **Build the Docker image**:
   ```bash
   docker build -t js-express-server .
   ```

2. **Run the Docker container**:
   ```bash
   docker run -p 8001:8001 js-express-server
   ```

The server will be accessible at `http://localhost:8001`.

## License

This project is licensed under the MIT License.