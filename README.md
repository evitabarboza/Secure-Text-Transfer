# Secure Text Transfer

This project implements a simple message processing system that allows users to send and receive messages seamlessly. 

## Flow

- **Sending Messages**: Users enter messages on the frontend, which are sent to the backend via a POST request (`/api/messages`). The backend processes the message (with optional encryption) and stores it in MongoDB. After successful storage, the frontend clears the input field.

- **Receiving Messages**: The frontend makes a GET request (`/api/messages`) to retrieve all stored messages from the backend, which are then displayed on the UI.

## Tech Stack

- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MongoDB

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the application:
   ```bash
   npm start
   ```

## Usage

- Submit a message using the input box.
- The backend processes and stores the message.
- View stored messages on the UI.

## License

This project is licensed under the MIT License.

## Contact Details 
For any inquiries, suggestions, or feedback, please contact me at:

- Email: evitabarboza195@gmail.com
- GitHub 1: Evita Barboza
- Github 2: msranjana
```
