# 🤖 SkyyRose Chatbot Frontend

A lightweight and stylish frontend interface for the **SkyyRose AI Assistant**, powered by ChatGPT. This project connects to a backend API (hosted on Render) to handle natural language queries from users, featuring a custom avatar and clean UI.

---

## 🌐 Live Preview

You can deploy this frontend to platforms like:

- [Vercel](https://vercel.com/)
- [Netlify](https://app.netlify.com/)
- [GitHub Pages](https://pages.github.com/)

---

## 🚀 Features

- Chat interface with input/output
- Avatar integration (`assets/skyyrose-avatar.png`)
- Asynchronous backend communication via `fetch()`
- Responsive design (desktop & mobile friendly)
- Easy to extend with styling or logic

---

## 📁 Folder Structure
skyyrose-chatbot-official-frontend/
├── index.html # Main HTML entry point
├── style.css # UI styling
├── script.js # Chat logic (calls backend)
└── assets/
└── skyyrose-avatar.png # Your AI avatar image

---

## ⚙️ How It Works

This frontend sends user messages to a backend API hosted at:

https://skyyrose-backend-official.onrender.com/chat

The backend responds with a reply, which is displayed along with the Skyy Rose avatar.

---

## 📦 Setup Instructions

### 1. Clone the Repo

```bash
git clone https://github.com/SkyyRoseLLC/skyyrose-chatbot-official-frontend.git
cd skyyrose-chatbot-official-frontend



