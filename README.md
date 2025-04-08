# 🎬 BingeMovie

**BingeMovie** is a full-stack web application for movie ticket booking. It provides an interactive interface for users to book and cancel tickets, while giving administrators control to manage movie listings.

---

## 🚀 Tech Stack

**Frontend**  
- React.js  
- Axios  
- CSS/Bootstrap  

**Backend**  
- Node.js  
- Express.js  
- MongoDB (via Mongoose)

---

## 🧩 Features

- Two user roles: **User Panel** and **Admin Panel**
- **Users** can:
  - Register/login
  - View recent movies
  - Book or cancel movie tickets  
- **Admins** can:
  - Add, update, or remove movies from the system
  - View all bookings and manage data

---

## 📦 How to Run the Project

### Backend

1. Navigate to the backend folder:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up environment variables (e.g., `.env` file):
   ```env
   MONGO_URL=your_mongodb_connection_string
   PORT=5000
   ```

4. Start the server:
   ```bash
   npm start
   ```

---

### Frontend

1. Navigate to the frontend folder:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the React app:
   ```bash
   npm start
   ```

4. Access the app at:
   ```
   http://localhost:3000
   ```

---

## 🔗 API Structure

- `GET /movies` - Get all movies
- `POST /booking` - Book a ticket
- `DELETE /booking/:id` - Cancel a booking
- `POST /admin/add` - Admin adds movie
- `DELETE /admin/remove/:id` - Admin removes movie
- User auth, admin auth routes...

---

## 👨‍💻 Author

**Sourav Kumar**  
[GitHub: Sk-SouravKumar](https://github.com/Sk-SouravKumar)

