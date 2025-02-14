# **FinTrackAI - Smart Expense Tracker & AI Insights** 💰📊

## **🚀 About FinTrackAI**
FinTrackAI is a **full-stack FinTech expense tracker** that helps users **manage their finances**, track **income & expenses**, and receive **AI-powered spending insights**. It supports **real-time notifications**, **cloud storage for receipts**, and works across **web and mobile (Flutter) platforms**.

## **🌟 Features**
✅ **User Authentication & RBAC** (JWT-based login, User & Admin roles)  
✅ **Expense & Income Management** (CRUD operations)  
✅ **AI-Powered Expense Insights** (OpenAI API / ML.NET integration)  
✅ **Real-Time Notifications** (via SignalR)  
✅ **Kanban-style Task Management** (Vue 3 Drag & Drop UI)  
✅ **Cloud Storage for Receipts** (Azure Blob Storage)  
✅ **Web & Mobile Sync** (REST API + Flutter App)  
✅ **Role-Based Access Control (RBAC)**  

---

## **📦 Tech Stack**
### **🔹 Backend: ASP.NET Core (C#) API**
- **ASP.NET Core 8.0 Web API**
- **Entity Framework Core (MSSQL Database)**
- **JWT Authentication & Authorization**
- **SignalR for Real-time Events**
- **Azure Blob Storage for File Uploads**
- **OpenAI API for AI Spending Insights**

### **🔹 Frontend: Vue 3 + TypeScript**
- **Vue 3 (Composition API, Pinia State Management)**
- **Vite + TypeScript for Development**
- **Axios for API Requests**
- **TailwindCSS for UI Design**

### **🔹 Mobile App: Flutter**
- **Flutter + Riverpod (State Management)**
- **Dio for HTTP Requests**
- **Secure Storage for JWT Tokens**
- **Firebase Push Notifications**

---

## **📂 Project Structure**

```plaintext
📦 FinTrackAI/
 ┣ 📂 Backend (ASP.NET Core API)
 ┃ ┣ 📂 Controllers/
 ┃ ┣ 📂 Models/
 ┃ ┣ 📂 Services/
 ┃ ┣ 📂 Repositories/
 ┃ ┣ 📂 SignalR/
 ┃ ┗ 📜 Program.cs
 ┣ 📂 Frontend (Vue 3)
 ┃ ┣ 📂 components/
 ┃ ┣ 📂 pages/
 ┃ ┣ 📂 store/
 ┃ ┗ 📜 main.ts
 ┣ 📂 Mobile (Flutter)
 ┃ ┣ 📂 screens/
 ┃ ┣ 📂 models/
 ┃ ┣ 📂 services/
 ┃ ┗ 📜 main.dart
```

---

## **⚡ Installation & Setup**

### **1️⃣ Backend (ASP.NET Core API)**
```sh
cd Backend
# Install dependencies
dotnet restore
# Run the API
dotnet run
```

### **2️⃣ Frontend (Vue 3 + TypeScript)**
```sh
cd Frontend
# Install dependencies
npm install
# Run the app
npm run dev
```

### **3️⃣ Mobile App (Flutter)**
```sh
cd Mobile
# Install dependencies
flutter pub get
# Run the app
flutter run
```

---

## **🌍 API Endpoints**

| Method | Endpoint | Description |
|--------|---------|-------------|
| `POST` | `/api/auth/register` | Register new user |
| `POST` | `/api/auth/login` | User login (JWT) |
| `GET` | `/api/expenses` | Get all expenses |
| `POST` | `/api/expenses` | Add new expense |
| `GET` | `/api/income` | Get all income records |
| `POST` | `/api/income` | Add new income |
| `GET` | `/api/reports` | Get AI-based spending insights |
| `GET` | `/api/notifications` | Get real-time budget alerts |

---

**📢 Want to contribute?** Fork the repo, make a pull request, and let’s build together! 🎯

---

## **📢 Contact & Support**
📧 **Email:** [work@ilhanklisura.com](mailto:work@ilhanklisura.com)  
💼 **LinkedIn:** [Check me out here!](https://linkedin.com/in/ilhanklisura/)

