# Real Chat App

## Overview

Real Chat App is a modern chat application that allows users to communicate in real-time. It is built using React with Context API for state management and Node.js with Express for the server-side.

## Features

- User authentication and registration
- Real-time messaging
- Group chats
- User profiles
- Message history

## Technologies Used

- **Front-end**: React, Context API, Socket.IO
- **Back-end**: Node.js, Express
- **Database**: MongoDB

---

## Installation

### Back-end Setup

1. Navigate to the back-end directory:

   ```bash
   cd back-end
   ```

2. Create a `.env` file with the following content:

   ```plaintext
   API_KEY="AIzaSyDAQ8irxkxPD5Nn6mqqwZxMOdjREzByyNU"
   SESSIONS_SECRET_KEY="manchester city is best team in the world"
   DB_URL="mongodb+srv://2022170867:5MmUYmD4ElTkEtb7@chat.tq4eg.mongodb.net/?retryWrites=true&w=majority&appName=chat"
   email="emam200232@gmail.com"
   password="ktgw swje ckmz yjyo"
   forget_name="now i became death i became destroyer of the world"
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the server:

   ```bash
   npm start
   ```

### Front-end Setup

1. Navigate to the front-end directory:

   ```bash
   cd front-end
   ```

2. Install dependencies (including a specific library with `--force`):

   ```bash
   npm i react-verification-code-input --force
   ```

3. Start the application:

   ```bash
   npm start
   ```

## Usage

Once both the front-end and back-end are running:

Open your browser and go to `http://localhost:3000` to access the application.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch:

   ```bash
   git checkout -b feature/YourFeature
   ```

3. Commit your changes:

   ```bash
   git commit -m 'Add YourFeature'
   ```

4. Push to the branch:

   ```bash
   git push origin feature/YourFeature
   ```

5. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Socket.IO for real-time communication
- React Router for navigation
- Context API for state management
