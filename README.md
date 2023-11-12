# Employee Management System

This is a full-stack Employee Management System implemented using Node.js, Express.js, MongoDB for the backend, and React.js for the frontend.

## Table of Contents
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [License](#license)

## Features
- CRUD Operations: Create, Read, Update, and Delete employee records.
- Pagination: Efficiently handle a large number of employee records with pagination.
- Employee Listing: Display employees by department, title, location, etc.
- Client-Side Routing: Utilize React Router for seamless navigation within the application.
- User-Friendly UI: Present employee information including names, pictures, and job titles.
- Search Functionality: Easily search for employees based on various criteria.
- Responsive Design: Employ Tailwind CSS for a mobile-friendly and responsive user interface.

## Prerequisites
Ensure you have the following installed on your machine:
- [Node.js](https://nodejs.org/)
- [MongoDB](https://www.mongodb.com/try/download/community)

## Installation

### Backend (Node.js and Express)
1. Clone the repository:
   ```bash
   git clone https://github.com/umer1o9/employee-directory.git
   ```
    ```
    unzip employee-directory.zip
    ```
2. Navigate to the backend directory:
   ```bash
   cd employee-directory/employee-directory
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the server:
   ```bash
   npm start
   ```

### Frontend (React.js)
    ```
    unzip server.zip
    ```
1. Navigate to the frontend directory:
   ```bash
   cd employee-directory/frontend
   ```
   
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React development server:
   ```bash
   npm start
   ```

## Configuration
Configure the backend API URL in the frontend.
Open `employee-directory/frontend/src/config.js` and update the `API_URL` variable with your backend API URL.

Example:
```javascript
const API_URL = "http://localhost:3001";
export default API_URL;
```

## Usage
Access the application by opening the URL in your web browser:
- Frontend: [http://localhost:3000](http://localhost:3000)
- Backend: [http://localhost:3001](http://localhost:3001)

## API Documentation
API documentation can be found in the [API_DOCS.md](/backend/API_DOCS.md) file.

## License
This project is licensed under the [MIT License](LICENSE).
```
Make sure to replace `https://github.com/umer1o9/employee-directory.git` with the actual URL of your GitHub repository. Also, update any other placeholders with the relevant information. Additionally, you might want to create an `API_DOCS.md` file in the `backend` directory to document your API routes and endpoints.
