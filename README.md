
A full-stack web application with a React + Vite frontend and a Node.js backend.

---

## Project Structure

```
Assigments-main/
├── FRONTEND/   # React + Vite application
└── BACKEND/    # Node.js backend server
```

---

## Frontend Setup

The frontend is built with **React**, **Vite**, **Tailwind CSS**

### 1. Navigate to the frontend directory

```bash
cd FRONTEND
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the development server

```bash
npm run dev
```




---

## Backend Setup

The backend is a **Node.js** server that provides the API consumed by the frontend.

### 1. Navigate to the backend directory

```bash
cd BACKEND
```

### 2. Install dependencies

```bash
npm install
```

### 3. Configure environment variables

Create a `.env` file in the `BACKEND` directory and add the required variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

> **Note:** Never commit your `.env` file to version control.

### 4. Start the backend server

```bash
# Development mode (with auto-restart on file changes)
npm run dev

# OR production mode
npm start
```

The server will be running at **http://localhost:5000** by default.

```


