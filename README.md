# 🚀 APIForge AI

> AI-powered platform that automatically generates API documentation, interactive API explorers, and client SDKs from backend code.

---

## 📌 Overview

**APIForge AI** is a full-stack developer tool that analyzes backend code and automatically generates:

* 📄 API Documentation (OpenAPI/Swagger)
* 🧪 Interactive API Explorer (like Postman)
* 📦 Client SDKs (JavaScript, Python, Java)

This eliminates the need for manual API documentation and speeds up development.

---

## 🎯 Problem Statement

Develop a system that automatically generates comprehensive API documentation, interactive API explorers, and client SDKs by analyzing backend code, route definitions, and data models.

---

## 💡 Solution

APIForge AI:

* Upload backend code (ZIP)
* Automatically detects API endpoints
* Generates OpenAPI documentation
* Provides an interactive API testing interface
* Creates ready-to-use SDKs

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* Axios

### Backend

* Node.js
* Express.js
* Multer (file upload)
* Unzipper (file extraction)

### AI (Optional Integration)

* OpenAI API (for smart documentation generation)

---

## 📁 Project Structure

```
autoapi-gen/
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── services/
│   └── server.js
│
├── frontend/
│   ├── pages/
│   ├── components/
│   └── styles/
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/apiforge-ai.git
cd apiforge-ai
```

---

### 2️⃣ Backend Setup

```bash
cd backend
npm install
node server.js
```

Server runs on:
👉 http://localhost:5000

---

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:
👉 http://localhost:3000

---

## 🚀 How to Use

1. Upload a backend ZIP file
2. Click **Analyze API**
3. View detected endpoints
4. Generate API documentation
5. Test APIs using explorer
6. Download SDKs

---

## 📦 Features

* ✅ Automatic API detection
* ✅ OpenAPI (Swagger) generation
* ✅ Interactive API explorer
* ✅ SDK generation
* ✅ File upload & extraction

---

## 🔥 Future Enhancements

* 🤖 AI-generated API descriptions
* 🔐 Authentication detection (JWT/OAuth)
* 📊 API version comparison
* 📁 Postman collection export
* 🎨 Advanced UI with Tailwind CSS

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed for Hackathon 🚀
