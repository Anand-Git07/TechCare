# TechCare



Features
AI chat assistant to take guidance about mental health.
Analyse your mental health over a period of time.
Get an Indication about your mental health condition with a graphical visualization.
Editor's compiled articles to read and educate about mental health problems.
Get emails from time to time with suggestions to improve your mental health.
Tech
System Design
MindMate application runs on 4 server

Frontend
Backend
WebSocket Server
Email Server des
Tech stack
Frontend
React JS
Tailwind
Backend
Node Js
Express Js
Gemini (Gen AI)
Web Sockets
Node Mailer
Tools
Vercel
Render
Mongo DB
Firebase
How to Setup Locally?
Firebase Setup
Setup a new Firebase project
Add a Web App
Go to Authentication -> Sign-in Method
Enable Email/Password, Gmail as Provider
Go to the Project Settings of Web App and get your firebaseConfig object
Create .env in Frontend folder and add firebaseConfig as per .env.sample file
In the service accounts section, Generate new private key (json object).
Create .env in Backend folder and add new private key as per .env.sample file
Fill rest .env as per .env.sample files
Gemini Setup
Get your Gemini (by Google) API_KEY from (https://ai.google.dev) and put in Backend .env as per .env.sample
MongoDB Setup
Create a MongoDB Atlas (https://www.mongodb.com) account and get your URI and put in Backend .env as per .env.sample
Create Connection amongst Servers
Put Url for Websocketserver in Backend .env (ex- WEBSOCKET_SERVER=ws://localhost:8802)
Put Url for Backend and Websocketserver in Frontend .env (ex- REACT_APP_API_LINK=http://localhost:8800 and REACT_APP_WS_LINK=ws://localhost:8802)
Scripts to Install and Run
Need to have Node.js installed
Go to the Backend, Frontend, Websockerserver folder seperately and run for each npm install
Run Backend by, npm run dev or npm start
Run Frontend by, npm start
Run Websocketserver by, node index.js
