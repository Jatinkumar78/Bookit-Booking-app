# BookIt - Hotel and Room Booking Web App

BookIt is a modern web application built with the MERN stack, providing users with an intuitive platform to browse, search, and book hotels or rooms effortlessly. With a sleek interface and powerful backend, BookIt ensures a seamless booking experience for all users.

## Features

- **User-Friendly Interface**: A responsive and intuitive front-end for easy navigation.
- **Real-Time Booking**: Search and book accommodations in real-time.
- **Secure Data Management**: Robust back-end with MongoDB to store and manage user and booking data securely.
- **Dynamic Functionality**: API integrations for enhanced user experience and performance optimization.

## Technologies Used

- **Frontend**: React.js, HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **State Management**: Context API/Redux (if applicable)
- **Package Manager**: Yarn/npm

## Installation and Setup

Follow these steps to run the project locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/bookit.git
   cd bookit
   ```

2. **Install Dependencies**:
   For the server:
   ```bash
   cd server
   npm install
   ```
   For the client:
   ```bash
   cd client
   npm install
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the server directory and add the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Run the Application**:
   Start the server:
   ```bash
   npm run dev
   ```
   Start the client:
   ```bash
   npm start
   ```

   The application will be accessible at `http://localhost:3000`.

## Project Structure

```plaintext
BookIt/
|-- client/      # Frontend React application
|-- server/      # Backend Node.js application
|-- .env         # Environment variables
|-- package.json # Dependency files
```

## Screenshots

![Screenshot (119)](https://github.com/user-attachments/assets/1478bdd4-ec5b-473f-a0a0-9eeea34ca9d5)


## Contributions

Contributions are welcome! Feel free to fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Developed with ❤️ by [Jatin Kumar](mailto:activejatinkumar2274@gmail.com).
