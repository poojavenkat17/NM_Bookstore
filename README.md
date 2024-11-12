

# Bookstore Project

## Overview

This project is a full-stack bookstore application, allowing users to browse, search, and manage a collection of books. It uses Node.js and Express for the backend API, MongoDB for data storage, and a React frontend styled with Tailwind CSS.

## Project Structure

```
book-store/
├── backend/
│   ├── models/
│   │   └── bookModel.js          # Defines the MongoDB schema for book documents
│   ├── routes/
│   │   ├── booksRoute.js         # Handles book-related API routes (CRUD operations)
│   │   └── index.js              # Sets up backend API routes and server configuration
├── frontend/
│   ├── public/                   # Holds static files like images, icons, etc.
│   ├── src/                      # Main frontend application code
│   ├── .eslintrc.cjs             # ESLint configuration for code quality and standards
│   ├── index.html                # Main HTML file to load the React app
│   ├── package-lock.json         # Auto-generated dependencies lock file for frontend
│   ├── package.json              # Holds project details and dependencies for frontend
│   ├── postcss.config.js         # Configuration for PostCSS (used with Tailwind CSS)
│   ├── README.md                 # Project description and usage instructions
│   ├── tailwind.config.js        # Tailwind CSS configuration file
│   ├── vite.config.js            # Vite configuration for development and build
│   └── .gitignore                # Specifies files to ignore in version control
```

## Installation

1. **Clone the repository to your local machine**:
   ```bash
   git clone https://github.com/poojavenkat17/NM_Bookstore.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd book-store
   ```

3. **Install dependencies**:
   - Backend:
     ```bash
     npm install
     ```
   - Frontend:
     ```bash
     cd frontend
     npm install
     ```

4. **Create a `.env` file in the root directory**:
   ```
   PORT=3000
   mongoDBURL=your_mongodb_url
   ```
   Replace `your_mongodb_url` with the URL of your MongoDB database.



## Running the Application

1. **Start the backend server**:
   ```bash
   npm run dev
   ```

2. **Start the frontend**:
   ```bash
   cd frontend
   npm run dev
   ```

3. **View the application**:
   - Open your browser and navigate to `http://localhost:5173`.

## Usage

- **User**: Browse the collection of books through cards and tables, view detailed descriptions, and add books to your cart for purchase.
- **Admin**: Access the admin panel by logging in with your credentials. Manage books by creating new ones, editing existing entries, or deleting books from the collection.

## Technologies Used

- **Backend**: Node.js, Express, MongoDB
- **Frontend**: React
