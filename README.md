## Expense Tracker Application

This is a web application built with Node.js and Express. It features user authentication, expense tracking, and income management. The application uses a MySQL database for session management and data storage.

## Features

- User authentication
- Expense tracking
- Income management
- Session management with MySQL

## Technologies Used

- Node.js
- Express.js
- MySQL
- dotenv
- body-parser
- express-session

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Node.js (>= 14.x)
- MySQL server

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
Install the dependencies:

bash
Copy code
npm install
Create a .env file in the root directory and configure your database connection and session secret. Here’s a sample .env file:

plaintext
Copy code
DB_HOST=your_db_host
DB_PORT=your_db_port
DB_USER=your_db_user
DB_PASSWORD=your_db_password
DB_NAME=your_db_name
SESSION_SECRET=your_session_secret
Running the Application Locally
To run the application locally, use the following command:

bash
Copy code
npm start
By default, the application will run on http://localhost:3000. You can navigate to this URL in your browser to access the login page.

Vercel Live Link
You can also access the live version of the application at the following link:
https://deployment-week8.vercel.app/

