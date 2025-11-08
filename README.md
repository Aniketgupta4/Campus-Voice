# 🎓 College Support Chatbot System

![HTML5](https://img.shields.io/badge/HTML5-orange?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-blue?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-lightgreen?logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-green?logo=mongodb&logoColor=white)
![Open Source](https://img.shields.io/badge/Open%20Source-💻-brightgreen)
![Made with ❤️ by Aniket](https://img.shields.io/badge/Made%20with-❤️-red)

> 🤖 A **college support chatbot** designed to resolve student issues, answer real-world queries, and provide management dashboards for **Students**, **HOD**, and **Principal**. Chat interface is similar to **WhatsApp minimized chats** for ease of use.

---

## 🚀 **Overview**

This project is a **full-stack chatbot system** built for colleges with the following features:

- 💬 **Chatbot interface** for students with minimized WhatsApp-like chat bubbles  
- 🧩 Handles **real-world and college-related queries**  
- 📊 **Three dashboards**:
  - **Student**: Ask queries, view responses  
  - **HOD**: View student queries, respond, track issues  
  - **Principal**: Monitor overall queries, stats, escalate important issues  
- ⚡ Real-time chat with **Node.js** and **Socket.IO**  
- 🗄️ Data management using **MongoDB**  

This system is perfect for automating **student support** and **college administration communication**.

---

## 🧰 **Tech Stack**

| Tech | Description |
|------|-------------|
| 🟢 Node.js | Backend server and API handling |
| ⚙️ Express.js | Server routing and middleware |
| 🔌 Socket.IO | Real-time chat communication |
| 🗄️ MongoDB | Store users, queries, and chat history |
| 🎨 HTML/CSS | Chat UI and dashboard styling |
| ⚡ JavaScript | Frontend interactivity |
| 🖥️ EJS / React (optional) | Dynamic rendering of dashboards |

---

## ⚙️ **Features**

- ✅ Student login/signup  
- ✅ WhatsApp-style minimized chat interface  
- ✅ Ask queries related to college or real-world issues  
- ✅ HOD dashboard to manage student queries  
- ✅ Principal dashboard for monitoring overall activity  
- ✅ Real-time updates with Socket.IO  
- ✅ Query escalation from HOD to Principal  

---

## ⚙️ **How It Works**

1. **User Roles & Authentication**
   - Users sign up as **Student**, **HOD**, or **Principal**  
   - Session-based login using **express-session**  

2. **Student Dashboard**
   - Type query in chat interface  
   - Queries are sent to HOD in real-time  
   - Responses appear in minimized chat style  

3. **HOD Dashboard**
   - View all student queries  
   - Respond or escalate queries to Principal  
   - Track query status (pending/resolved/escalated)  

4. **Principal Dashboard**
   - Monitor all escalated queries  
   - Approve, reject, or provide additional instructions  

5. **Real-time Communication**
   - Socket.IO updates chat messages instantly  
   - MongoDB stores chat history and query metadata  

---

## 💻 **Setup & Usage**

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/college-chatbot.git
cd college-chatbot
