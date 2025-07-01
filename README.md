# React + Vite


#  FLIPR Full Stack Development Task

## 🌐 Deployed Link
**Frontend & Admin Panel:**  
🔗 [https://flipr-task-pearl.vercel.app/](https://flipr-task-pearl.vercel.app/)

---

## Repository
GitHub Repository: [https://github.com/1925YSH/FLIPR-TASK](https://github.com/1925YSH/FLIPR-TASK)

---

##  Project Overview

This is a full-stack MERN (MongoDB, Express.js, React.js, Node.js) web application created as part of the Flipr Placement Full Stack Task. It includes:

- A **Landing Page** for users to:
  - View projects
  - Read client testimonials
  - Submit a contact form
  - Subscribe to a newsletter

- An **Admin Panel** to:
  - Add and manage projects
  - Add and manage clients
  - View contact form submissions
  - View newsletter subscribers

---

##  Features

###  Landing Page
- **Projects Section**: Showcases all projects from backend.
- **Happy Clients Section**: Displays client feedback and info.
- **Contact Form**: Submits user details to backend.
- **Newsletter Section**: Allows email subscription.

### 🛡 Admin Panel
- **Project Management**: Add and view projects.
- **Client Management**: Add and view client details.
- **Contact Form Responses**: View submitted user info.
- **Newsletter Subscriptions**: View all subscribed emails.

---

## 🛠 Tech Stack

| Layer       | Technology Used              |
|-------------|------------------------------|
| Frontend    | React.js, Tailwind CSS        |
| Backend     | Node.js, Express.js          |
| Database    | MongoDB Atlas (Cloud-hosted) |
| Deployment  | Frontend: Vercel, Backend: Render |

--

##  Folder Structure

```
/client         --> React frontend
/server         --> Express backend
/models         --> MongoDB Mongoose Schemas
/routes         --> API Routes for projects, clients, contact, newsletter
/controllers    --> Logic for each route
```

---

##  Testing
- APIs tested using Postman
- Forms validated with both frontend and backend checks
- UI tested on various screen sizes and browsers

---

## ⚙️ How to Run Locally

1. **Clone the repo:**
   ```bash
   git clone https://github.com/1925YSH/FLIPR-TASK.git
   ```

2. **Navigate to client and install frontend dependencies:**
   ```bash
   cd client
   npm install
   ```

3. **Navigate to server and install backend dependencies:**
   ```bash
   cd ../server
   npm install
   ```

4. **Setup environment variables in `/server/.env`:**
   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=5000
   ```

5. **Run backend:**
   ```bash
   npm run dev
   ```

6. **Run frontend:**
   ```bash
   cd ../client
   npm run dev
   ```

---

## 📩 Contact

For any queries or suggestions, feel free to reach out via the contact form on the deployed website.

---

## 📄 License

This project is submitted as part of the Flipr Placement Drive. All rights reserved by the developer.

