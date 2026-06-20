# Task Manager Application

A full-stack Task Manager web application built using React.js, Node.js, Express.js, MongoDB, and JWT Authentication.
Users can register, log in securely, create tasks, update tasks, delete tasks, and manage their daily workflow efficiently.

---

# Features

* User Authentication (Signup & Login)
* JWT-based Authorization
* Protected Routes
* Add New Tasks
* Update Existing Tasks
* Delete Tasks
* View All Tasks
* Loading Spinner Support
* Responsive UI Design
* MongoDB Database Integration

---

# Tech Stack

## Frontend

* React.js
* React Router DOM
* Axios
* CSS3
* js-cookie

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* bcrypt
* dotenv
* cors

---

# Project Structure

## Frontend

```bash
src/
│
├── apis/
├── components/
├── pages/
├── styling/
├── App.js
└── index.js
```

## Backend

```bash
server/
│
├── index.js
├── .env
├── package.json
```

---

# Installation

## Clone Repository

```bash
git clone <repository-url>
```

---

# Frontend Setup

## Navigate to frontend

```bash
cd frontend
```

## Install Dependencies

```bash
npm install
```

## Start Frontend

```bash
npm start
```

Frontend runs on:

```bash
http://localhost:3000
```

---

# Backend Setup

## Navigate to backend

```bash
cd backend
```

## Install Dependencies

```bash
npm install
```

## Create .env File

```env
MONGOURL=your_mongodb_connection_url
PORT=4000
SECRETKEY=your_secret_key
```

## Start Backend

```bash
node index.js
```

Backend runs on:

```bash
http://localhost:4000
```

---

# API Endpoints

## Authentication

### Signup

```http
POST /signup
```

### Login

```http
POST /login
```

---

## Tasks

### Get All Tasks

```http
GET /tasks
```

### Add Task

```http
POST /addtask
```

### Update Task

```http
PUT /update/:id
```

### Delete Task

```http
DELETE /delete/:id
```

---

# Authentication

Protected routes require JWT token in headers.

Example:

```javascript
headers: {
   Authorization: `Bearer ${jwtToken}`
}
```

---

# Screenshots
<img width="1918" height="870" alt="Screenshot 2026-06-20 161936" src="https://github.com/user-attachments/assets/0cb67133-36fb-481b-9ab1-b75621625f8e" />
<img width="1917" height="968" alt="Screenshot 2026-06-20 162024" src="https://github.com/user-attachments/assets/68868149-dfe3-4b9b-8139-e6bced103ac7" />
<img width="1913" height="966" alt="Screenshot 2026-06-20 162134" src="https://github.com/user-attachments/assets/01713f2c-0825-46f9-9517-73bdd298e603" />

<img width="1915" height="965" alt="Screenshot 2026-06-20 162154" src="https://github.com/user-attachments/assets/ad3dd853-89b8-4c07-9b95-df4b8d728d56" />
<img width="1918" height="962" alt="Screenshot 2026-06-20 162216" src="https://github.com/user-attachments/assets/53a6aaaf-219c-4efd-aa65-d4b1d162c4c3" />



---

# Future Improvements

* User-specific task management
* Task priority support
* Due date reminders
* Drag and Drop Tasks
* Dark Mode
* Search & Filter Tasks

---

# Author

Visweswar Reddy

---

# License

This project is open-source and available under the MIT License.
