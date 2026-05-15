# Realtime Chat & Video Platform 🚀

A full-stack, production-ready real-time communication platform featuring instant messaging and video conferencing capabilities.

## 🛠️ Tech Stack
- **Backend:** .NET 8 / Web API, SignalR (for WebSockets), Entity Framework Core.
- **Frontend:** React.js / Angular (اكتب التقنية اللي مستخدمها في الـ Client).
- **Database:** SQL Server / PostgreSQL.

## ✨ Features
- **Real-time Messaging:** Instant chat delivery using SignalR.
- **Video Calling:** Peer-to-peer video/audio communication (WebRTC).
- **Architecture:** Clean Architecture with robust repository pattern.

## 🚀 How to Run Locally

### Backend (API)
1. Navigate to the API folder: `cd API`
2. Update the connection string in `appsettings.json`.
3. Run migrations: `dotnet ef database update`
4. Start the server: `dotnet run`

### Frontend (Client)
1. Navigate to the Client folder: `cd Client`
2. Install dependencies: `npm install`
3. Start the app: `npm start`
