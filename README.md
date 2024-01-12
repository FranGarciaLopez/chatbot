# README.md - Chatbot Project with Node.js and TursoDB

## Main Objective

The main goal of this project was to develop a chatbot using Node.js and TursoDB. It functions as a real-time chat where two instances can be opened and receive messages from each other.

## Technologies Used

- **Node.js:** Development platform.
- **TursoDB:** Database management system.
- **JavaScript:** Programming language used.
- **Libraries:**
  - `express`: Framework for the server.
  - `socket.io`: Enables real-time communication between the client and the server.
- **Random-data API:** Consulted to generate random users.

## Database

The database consists of 1 table with the following 3 columns:
- `id`: Unique identifier of the message.
- `message`: Content of the message.
- `user`: User sending the message.

## Environment Variables

`.dotenv` is used to manage and securely store environment variables.

## Frontend

The frontend design was done using:
- **HTML:** For the page structure.
- **CSS:** For style and visual design.
