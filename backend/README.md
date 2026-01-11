## 📌 Project Overview  

Welcome to **WorkNest**, a powerful and scalable multi-tenancy project management system built with **Node.js**, **MongoDB**, and **React**. Designed for real-world B2B needs, this project delivers features like Google Sign-In, workspace management, project tracking, task collaboration, role-based permissions, and more. Perfect for developers aiming to create SaaS-based team collaboration platforms.  

---

## 🌟 Key Features  

- 🔐 **Authentication** (Google Sign-In, Email, Password)  
- 🏢 **Create & Manage Multiple Workspaces**  
- 📊 **Projects & Epics Management**  
- ✅ **Tasks** (CRUD, Status, Priority, Assignee)  
- 👥 **Roles & Permissions** (Owner, Admin, Member)  
- ✉️ **Invite Members to Workspaces**  
- 🔍 **Filters & Search** (Status, Priority, AssignedTo)  
- 📈 **Analytics Dashboard**  
- 📅 **Pagination & Load More**  
- 🔒 **Cookie Session Management**  
- 🚪 **Logout & Session Termination**  
- 🌱 **Seeding** for Test Data  
- 💾 **Mongoose Transactions** for Robust Data Integrity  
- 🌐 **Built with MERN Stack** (Node.js, MongoDB, React, TypeScript)  

---

## 🚀 Tools & Technologies  

This project leverages the latest tools and frameworks for modern development:  

- **Node.js**: Scalable backend architecture  
- **React.js**: Dynamic frontend framework  
- **MongoDB & Mongoose**: Flexible and scalable database solutions  
- **Google OAuth**: Seamless Google Sign-In integration  
- **TypeScript**: For a type-safe codebase  
- **TailwindCSS & Shadcn UI**: Beautiful, responsive design  
- **Vite.js**: Lightning-fast frontend development  

---

## 🔄 Getting Started  

### 1. Clone the Repository

```bash
git clone https://github.com/Ninjasri98/WorkNest
cd WorkNest
```

### 2. Set Up Environment Variables  

Create a `.env` file in the root of the backend folder and configure these variables:  

```plaintext  
PORT=8000
NODE_ENV=development
MONGO_URI="mongodb+srv://<username>:<password>@<>.mongodb.net/worknest_db"  

SESSION_SECRET="session_secret_key"

GOOGLE_CLIENT_ID=<your-google-client-id>  
GOOGLE_CLIENT_SECRET=<your-google-client-secret>  
GOOGLE_CALLBACK_URL=http://localhost:8000/api/auth/google/callback

FRONTEND_ORIGIN=http://localhost:3000
FRONTEND_GOOGLE_CALLBACK_URL=http://localhost:3000/google/callback
```
Create a `.env` file in the root of the client folder and configure these variables:
```plaintext
VITE_API_BASE_URL="http://localhost:8000/api"
```

### 3. Run the Application  

Install dependencies and start the development server:  

```bash
cd client
npm install  
npm run dev  
```  

Access the backend at `http://localhost:8000`.  

---

## 🌐 Deploying WorkNest  

### 1. Add Environment Variables  
Add the `.env` variables to your hosting platform (e.g., Vercel).  

### 2. Deploy  
Deploy your app using your preferred method to make it live.  

---
