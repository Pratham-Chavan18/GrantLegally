# ⚖️ GrantLegally

<p align="center">
  <strong>AI-Powered Legal Intelligence Platform for the Indian Judiciary</strong>
</p>

<p align="center">
  Intelligent document analysis • AI Legal Assistant • Bail Recommendation • Case Search • Analytics
</p>

---

## 📌 Overview

GrantLegally is a full-stack Legal Intelligence Platform designed to streamline legal workflows using Artificial Intelligence, Retrieval-Augmented Generation (RAG), and document intelligence.

The platform enables lawyers, judges, legal assistants, and citizens to efficiently upload legal documents, search precedents, generate AI-assisted insights, review bail applications, and interact with an intelligent legal chatbot.

---

## ✨ Features

### 🔐 Authentication
- JWT Authentication
- Secure Login & Registration
- Password Hashing using bcrypt
- Role-based access

### 📄 Document Intelligence
- Upload legal documents
- AI-powered document analysis
- IPC section identification
- Risk assessment
- Document status tracking

### 🤖 AI Legal Chat (RAG)
- Context-aware legal assistant
- ChromaDB vector search
- Citation-aware responses
- Suggested legal questions
- Conversation history

### ⚖️ Bail Recommendation
- Guided Bail Application Wizard
- AI-assisted recommendation
- Case information management

### 👨‍⚖️ Judge Review Dashboard
- Review pending applications
- Accept/Reject workflow
- Decision tracking

### 🔍 Precedent Search
- Semantic legal case search
- AI-powered retrieval
- Similar case recommendations

### 📊 Analytics Dashboard
- Case analytics
- Outcome distribution
- Usage statistics
- Cost monitoring
- IPC trends

### ⚙️ Settings
- User preferences
- Account management

---

# 🖥️ Pages

- Login
- Dashboard
- Documents
- Bail Wizard
- Judge Review
- Precedent Search
- AI Legal Chat
- Analytics
- Settings

---

# 🚀 Tech Stack

## Frontend

- React 19
- TypeScript
- Vite
- React Router
- Zustand
- Lucide Icons
- Vanilla CSS

## Backend

- FastAPI
- Python
- JWT Authentication
- bcrypt
- ChromaDB
- pdfplumber
- python-docx

---

# 🎨 UI Highlights

- Premium Dark Theme
- Liquid Glass Sidebar
- Glassmorphism Design
- Responsive Layout
- Micro Animations
- Interactive Dashboard
- Modern Design System
- Sparkline Charts
- Gradient Components

---

# 📂 Project Structure

```
LexCore-AI
│
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── store
│   │   ├── App.tsx
│   │   └── main.tsx
│   └── package.json
│
├── backend
│   ├── main.py
│   ├── auth.py
│   ├── config.py
│   ├── seed_data.py
│   └── requirements.txt
│
└── README.md
```

---

# 📡 API Endpoints

## Authentication

| Method | Endpoint |
|---------|----------|
| POST | `/api/v1/auth/login` |
| POST | `/api/v1/auth/register` |
| POST | `/api/v1/auth/refresh` |

---

## Documents

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/documents` |
| POST | `/api/v1/documents/upload` |
| POST | `/api/v1/documents/{id}/analyze` |

---

## Bail

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/bail/applications` |
| POST | `/api/v1/bail/applications` |
| PATCH | `/api/v1/bail/applications/{id}/status` |

---

## Search

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/search/precedents` |

---

## Chat

| Method | Endpoint |
|---------|----------|
| POST | `/api/v1/chat` |
| GET | `/api/v1/chat/history/{session}` |

---

## Analytics

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/analytics/dashboard` |

---

## Health

| Method | Endpoint |
|---------|----------|
| GET | `/api/v1/health` |

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/Pratham-Chavan18/GrantLegally.git

cd GrantLegally
```

---

## Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux / Mac
source venv/bin/activate

pip install -r requirements.txt

uvicorn main:app --reload
```

Backend runs at:

```
http://localhost:8000
```

Swagger Documentation:

```
http://localhost:8000/docs
```

---

## Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

Frontend:

```
http://localhost:5173
```

---

# 📈 Future Improvements

- AI Judgment Prediction
- Voice-based Legal Assistant
- OCR for Scanned Documents
- Multilingual Legal Support
- Court Calendar Integration
- Real-time Notifications
- Cloud Storage Integration
- E-signature Support
- Mobile Application

---

# 🤝 Contributing

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/new-feature
```

3. Commit your changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 📄 License

This project is intended for educational and research purposes.

---

# 👨‍💻 Author

**Pratham Chavan**

GitHub: https://github.com/Pratham-Chavan18

---

<p align="center">
Made with ❤️ using React, FastAPI, ChromaDB, and AI
</p>
