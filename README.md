# 💬 Chat CRUD App

A simple web-based chat application built with **Express.js**, **MongoDB**, and **EJS**. This project allows users to create, read, update, and delete chat messages. It's a mini version of a chat system like WhatsApp, focused on practicing CRUD operations and full-stack basics.

---

## 🚀 Features

- 📥 View all chat messages
- ➕ Create a new chat
- ✏️ Edit existing messages
- ❌ Delete any chat
- 🧱 MongoDB for data storage
- 🎨 EJS for templating
- 📁 MVC structure

---

## 📂 Folder Structure

├── models/ # Mongoose schema for Chat
├── public/ # Static assets (CSS)
├── views/ # EJS templates
│ ├── index.ejs
│ ├── new.ejs
│ └── edit.ejs
├── init.js # (Optional) DB seeding file
├── index.js # Main Express server file
├── package.json
└── .gitignore

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Templating:** EJS
- **Tools:** Git, npm

---

## 📦 Installation

1. **Clone the Repository**

```bash
git clone https://github.com/srnsksyp/chat-crud-app.git
cd chat-crud-app
```

2. **Install Dependencies**

```bash
npm install
```

3. **Start MongoDB**
  - Make sure MongoDB is running locally (mongodb://127.0.0.1:27017/whatsApp).

4. **Run the App**

```bash
node index.js
```
Server runs at: http://localhost:8080

---

## Usage
- Visit /chats to view all chat messages
- Use /chats/new to create a new message
- Click "Edit" or "Delete" to modify chats

## 🧠 Learning Goals
- RESTful routes  
- CRUD operations using Mongoose  
- EJS templating  
- Form handling in Express  
- MVC folder structure  

## 📸 Screenshots
You can add screenshots of your UI here after uploading images to the `public/` folder or using markdown image links.

## 🧑‍💻 Author
GitHub: [@srnsksyp](https://github.com/srnsksyp)

## 📃 License
This project is licensed under the MIT License.
