# QuickBite

QuickBite is a web application designed to help users order food quickly and efficiently. The project is divided into two main parts: the client (frontend) and the server (backend).

## Project Structure

### Client

The client side of the project is built using React. The folder structure is as follows:

```
QuickBite/client/
├── package.json
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
└── src/
    ├── App.js
    ├── index.css
    ├── index.js
    ├── api/
    │   └── index.js
    ├── components/
    │   ├── Button.jsx
    │   ├── Navbar.jsx
    │   ├── SignIn.jsx
    │   ├── SignUp.jsx
    │   └── ...
    ├── pages/
    │   └── ...
    ├── redux/
    └── utils/
```

### Server

The server side of the project is built using Node.js and Express. The folder structure is as follows:

```
QuickBite/server/
├── error.js
├── index.js
├── package.json
├── controllers/
│   ├── Food.js
│   └── User.js
├── middleware/
│   └── verifyUser.js
├── models/
│   ├── Food.js
│   ├── Orders.js
│   └── User.js
└── routes/
    ├── Food.js
    └── User.js
```

## Getting Started

### Prerequisites

- Node.js
- npm or yarn

### Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/your-username/QuickBite.git
    ```

2. Navigate to the client directory and install dependencies:

    ```sh
    cd QuickBite/client
    npm install
    ```

3. Navigate to the server directory and install dependencies:

    ```sh
    cd ../server
    npm install
    ```

### Running the Application

1. Start the client:

    ```sh
    cd QuickBite/client
    npm start
    ```

2. Start the server:

    ```sh
    cd ../server
    npm start
    ```

The client will be running on `http://localhost:3000` and the server will be running on `http://localhost:5000`.

## Available Scripts

### Client

- `npm start`: Runs the app in development mode.
- `npm test`: Launches the test runner in interactive watch mode.
- `npm run build`: Builds the app for production.
- `npm run eject`: Ejects the app from Create React App configuration.

### Server

- `npm start`: Starts the server.
- `npm run dev`: Starts the server in development mode with nodemon.

## Learn More

- [React documentation](https://reactjs.org/)
- [Node.js documentation](https://nodejs.org/)
- [Express documentation](https://expressjs.com/)

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

