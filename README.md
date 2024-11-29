# Book_Exchange



# Book Exchange System

A MERN stack application for exchanging books that includes features such as user authentication, book listing, searching, borrowing, and lending.

## Project Structure

- **Frontend**: React-based client application located in the `frontend` folder.
- **Backend**: Node.js/Express-based server located in the `backend` folder.

---

## Prerequisites

Before running the application, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- npm (comes with Node.js)
- MongoDB (for database)

---

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/bookexchangesystem.git
   cd bookexchangesystem
   ```

2. Install dependencies for both frontend and backend:

   ```bash
   cd frontend
   npm install
   cd ../backend
   npm install
   ```

3. Configure environment variables:

   - Create a `.env` file in the `backend` folder with the following:
     ```env
     MONGO_URI=<Your MongoDB Connection String>
     PORT=5000
     JWT_SECRET=<Your JWT Secret>
     ```
   - Replace placeholders with actual values.

---

## Running the Application

1. Start the **backend** server:

   ```bash
   cd backend
   npm start
   ```

2. Start the **frontend** application:

   ```bash
   cd frontend
   npm start
   ```

---

## Accessing the Application

- Frontend (React): Open [http://localhost:3000](http://localhost:3000) in your browser.
- Backend (API): Runs on [http://localhost:5000](http://localhost:5000) by default.

---

## Development Notes

- Make sure MongoDB is running locally or provide a remote connection string in the `MONGO_URI`.
- Customize frontend and backend configurations as per your needs.

---

## Scripts

Here are some useful npm scripts:

### Frontend
- `npm start`: Starts the React development server.
- `npm run build`: Builds the React app for production.

### Backend
- `npm start`: Starts the Node.js server.
- `npm run dev`: Starts the server in development mode with live reload (requires `nodemon`).
