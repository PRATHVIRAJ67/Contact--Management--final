

# Contact Management Application

A full-stack Contact Management application that enables users to manage contact information. This application is built with **React** for the frontend and **Express.js** with **MongoDB** for the backend, allowing users to add, view, edit, and delete contacts with ease.

## Live Demo

Access the live application [Click here](https://contact-management-final.vercel.app/).

![Contact Management App Homepage](./contact%20Management.png)

---

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Running the Application](#running-the-application)

---

## Features

- **Add Contacts**: Users can add a new contact by providing details such as first name, last name, email, phone number, company, and job title.
- **View Contacts**: A paginated list of all contacts, with sortable columns to help users easily locate specific contacts.
- **Edit Contacts**: Modify existing contact information by clicking the edit icon next to each contact.
- **Delete Contacts**: Remove contacts from the database by clicking the delete icon, with a confirmation prompt.
- **Responsive Design**: The layout is optimized for various screen sizes, ensuring usability on both desktop and mobile devices.
- **Material UI**: The application’s interface is styled with Material UI components, providing a clean and professional look.

## Technologies Used

- **Frontend:**
  - [React](https://reactjs.org/)
  - [Material-UI (MUI)](https://mui.com/)
  - [React Hooks](https://reactjs.org/docs/hooks-intro.html)
  
- **Backend:**
  - [Express.js](https://expressjs.com/)
  - [MongoDB](https://www.mongodb.com/)
  - [Mongoose](https://mongoosejs.com/)
  - [CORS](https://www.npmjs.com/package/cors)
  - [Dotenv](https://www.npmjs.com/package/dotenv)

## Installation

### Prerequisites

- **Node.js** (v14 or later)
- **npm** (v6 or later)
- **MongoDB Atlas** account or local MongoDB setup

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/contact-management-app.git
   cd contact-management-app
   ```

2. **Install Root Dependencies**

   ```bash
   npm install
   ```

3. **Install Backend Dependencies**

   Navigate to the `backend` directory and install dependencies.

   ```bash
   cd backend
   npm install
   cd ..
   ```

4. **Install Frontend Dependencies**

   Navigate to the `frontend` directory and install dependencies.

   ```bash
   cd frontend
   npm install
   cd ..
   ```

## Configuration

### Environment Variables

Create a `.env` file in the root directory of the project with the following content:

```env
# backend/.env

MONGO_URI=your_mongodb_connection_string
PORT=5000
```

- **MONGO_URI**: Your MongoDB connection string. If using MongoDB Atlas, it will look something like `mongodb+srv://<username>:<password>@cluster0.mongodb.net/<dbname>?retryWrites=true&w=majority`.
- **PORT**: The port on which the backend server will run. Default is `5000`.

**Note**: Ensure that the `.env` file is **not** committed to version control for security reasons.

## Running the Application


npm start
```



