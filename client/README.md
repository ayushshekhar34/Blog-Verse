# MERN Blog Application

A fully responsive **MERN stack blog platform** that allows users to create, edit, and delete posts with rich text formatting, manage profiles, and interact through comments and likes. The application includes secure authentication, admin features, and a modern UI.

---

## 🚀 Features

* **User Authentication**: Secure login/signup with **JWT Authentication** and **OAuth 2.0**.
* **Admin Capabilities**: Manage users and posts with elevated privileges.
* **Blog Management**: Create, update, delete, and search posts with rich text editing using **React Quill**.
* **User Interaction**: Add comments, likes, and engage with posts dynamically.
* **Profile Management**: Update user details, upload profile images, and manage accounts.
* **Media Uploads**: Secure image uploads with progress tracking.
* **Dark Mode**: Seamless light/dark theme support.
* **Responsive Design**: Optimized for mobile and desktop using **Tailwind CSS**.

---

## 🛠️ Tech Stack

* **Frontend**: React.js, Redux Toolkit, React Quill, Tailwind CSS
* **Backend**: Node.js, Express.js
* **Database**: MongoDB
* **Authentication**: JWT, OAuth 2.0
* **State Management**: Redux Toolkit

---

## 📂 Project Structure

```
mern-blog-app/
│── client/               # React frontend  
│   ├── src/  
│   │   ├── components/   # Reusable components  
│   │   ├── pages/        # Page-level components  
│   │   ├── redux/        # Redux slices & store  
│   │   ├── App.js        # Root React component  
│   │   └── index.js      # Entry point  
│  
│── server/               # Express backend  
│   ├── config/           # DB & env config  
│   ├── controllers/      # Route handlers  
│   ├── middleware/       # Auth & error handling  
│   ├── models/           # MongoDB schemas  
│   ├── routes/           # API routes  
│   └── server.js         # Entry point  
│  
└── README.md  
```

---

## 📌 Future Enhancements

* Full-text search with filters & tags.
* Real-time notifications (using Socket.IO).


---


