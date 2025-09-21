# 🌟 TechCare 

TechCare is a mental health AI-powered chat assistant that guides and helps users improve their mental wellbeing. It provides a user-friendly interface to **learn, track, and enhance mental health**.  



## ✨ Features

- 🤖 **AI chat assistant** for guidance on mental health.  
- 📊 **Analyze your mental health** over time.  
- 📈 **Graphical visualization** of mental health conditions.  
- 📚 **Curated articles** to educate about mental health problems.  
- 📧 **Periodic email suggestions** to improve mental wellbeing.  

---

## 🛠 Tech Stack

### Frontend
- React JS  
- Tailwind CSS  

### Backend
- Node.js  
- Express.js  
- Gemini (Google Gen AI)  
- WebSockets  
- NodeMailer  

### Tools & Platforms
- Vercel (Frontend deployment)  
- Render (Backend & WebSocket server deployment)  
- MongoDB Atlas (Database)  
- Firebase (Authentication & services)  

---

## 🏗 System Design

MindMate runs on **4 servers**:  

<details>
<summary>Click to expand</summary>

1. Frontend Server  
2. Backend Server  
3. WebSocket Server  
4. Email Server  

</details>

---

## ⚡ Setup Locally

<details>
<summary>Firebase Setup</summary>

1. Create a new Firebase project.  
2. Add a Web App.  
3. Go to Authentication → Sign-in Method, enable Email/Password and Gmail.  
4. Copy firebaseConfig from Project Settings → Web App.  
5. Create .env in Frontend folder and add the config (see .env.sample).  
6. In Service Accounts, generate a private key (JSON) and add it to Backend .env.  

</details>

<details>
<summary>Gemini Setup</summary>

- Get your Gemini API_KEY from https://ai.google.dev and add it to Backend .env.  

</details>

<details>
<summary>MongoDB Setup</summary>

1. Create a MongoDB Atlas account: https://www.mongodb.com.  
2. Get your URI and add it to Backend .env.  

</details>

<details>
<summary>Connecting Servers</summary>

- Add the WebSocket server URL in Backend .env:  
  WEBSOCKET_SERVER=ws://localhost:8802

- Add Backend and WebSocket server URLs in Frontend .env:  
  REACT_APP_API_LINK=http://localhost:8800  
  REACT_APP_WS_LINK=ws://localhost:8802  

</details>

---

## 🚀 Install & Run

> Prerequisite: Node.js installed

# Go to Backend, Frontend, and WebSocketServer folders separately
npm install

# Run Backend
npm run dev

# Run Frontend
npm start

# Run WebSocket Server
node index.js

---

✅ techcare makes mental health support simple, interactive, and data-driven!
