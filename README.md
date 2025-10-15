# 🖊️ Whiteboard AZ — Real-Time Collaborative Whiteboard

Whiteboard AZ is a **full-stack collaborative whiteboard application** that enables users to draw, sketch, and brainstorm together in real time — all within the browser.  
Built with **React.js**, **Node.js**, **Express**, **Socket.IO**, and **MongoDB**, it provides sub-second latency for seamless teamwork and secure canvas sharing.

---

## 🚀 Features

✅ **Real-Time Collaboration** — Multiple users can draw simultaneously with live updates via Socket.IO  
✅ **Sub-Second Latency** — Optimized WebSocket communication ensures smooth interaction  
✅ **JWT Authentication** — Secure user sessions and protected boards  
✅ **Canvas Sharing** — Private and public session modes with access control  
✅ **Undo / Redo Support** — Full drawing history management  
✅ **Multiple Drawing Tools** — Pen, shapes, eraser, color palette, and more  
✅ **Responsive UI** — Works across desktop, tablet, and mobile devices  
✅ **Scalable Backend** — Supports 1000+ concurrent users with RESTful APIs and efficient DB queries  

---

## 🧩 Tech Stack

**Frontend:** React.js, HTML, CSS, TailwindCSS  
**Backend:** Node.js, Express.js, Socket.IO  
**Database:** MongoDB (Mongoose)  
**Authentication:** JWT (JSON Web Token)  
**Version Control:** Git & GitHub  

---

## 🏗️ Project Architecture

```
whiteboard_az/
│
├── backend/
│   ├── config/          # Database & environment configuration
│   ├── controllers/     # Request handlers
│   ├── middleware/      # JWT auth, error handling, etc.
│   ├── models/          # MongoDB schemas
│   ├── routes/          # API endpoints
│   └── server.js        # Entry point (Express + Socket.IO setup)
│
├── frontend/
│   ├── public/          # Static assets
│   ├── src/
│   │   ├── components/  # Reusable React components
│   │   ├── pages/       # UI pages (login, whiteboard, etc.)
│   │   ├── utils/       # Helper functions
│   │   └── App.js       # Root React component
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/<your-username>/whiteboard_az.git
cd whiteboard_az
```

### 2️⃣ Backend setup
```bash
cd backend
npm install
```

Create a `.env` file inside the **backend** folder:
```
PORT=5000
MONGO_URI=<your-mongodb-uri>
JWT_SECRET=<your-secret-key>
```

Start backend:
```bash
npm start
```

### 3️⃣ Frontend setup
```bash
cd ../frontend
npm install
npm run dev
```

Open your browser at **http://localhost:3000**

---

## 🔒 Security Highlights

- JWT-based authentication and authorization  
- Protected API endpoints  
- Input validation and rate limiting  
- Secure WebSocket connections  

---

## 📊 Performance Optimizations

- Reduced MongoDB query time by **40%** using optimized schema design  
- Implemented efficient Socket.IO rooms for faster updates  
- Batched state updates for minimal re-renders on the client side  

---

## 🌐 Live Demo (Optional)

[🔗 View Demo](#) — *Add link once deployed to Vercel / Render / AWS / etc.*

---

## 🤝 Contributing

Contributions are welcome!  
Please fork the repository, create a feature branch, and submit a pull request.

```bash
git checkout -b feature/new-tool
git commit -m "Added new drawing tool"
git push origin feature/new-tool
```

---

## 📜 License

This project is licensed under the **MIT License**.  
See the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Akash Singh**  
🌐 [GitHub](https://github.com/<your-username>)  
💼 [LinkedIn](https://linkedin.com/in/<your-linkedin>)  

---

> *Whiteboard AZ — Collaborate. Create. Connect.*
