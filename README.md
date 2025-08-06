# 🧠 Research Assistant

**A powerful web extension backed by a Spring Boot API that helps users summarize any text they select on a webpage.**

## ✨ Features

- 📝 Select any text on any webpage and get an instant summary.
- ⚙️ Backend powered by a robust Spring Boot REST API.
- 🔐 Token-based communication between extension and backend.
- 📄 Easy-to-use browser extension interface.
- 🚀 Fast and responsive summarization using advanced NLP techniques.

---

## 🛠️ Tech Stack

### Backend (Spring Boot API)
- Java 17+
- Spring Boot
- Spring Web
- RESTful API architecture
- CORS support
- JSON (Jackson)
- OpenAI / Gemini API (optional – for text summarization)

### Browser Extension
- HTML, CSS, JavaScript
- Manifest v3
- Fetch API for backend communication
- Context menu integration

---

## 🔧 How It Works

1. **User selects text** on any webpage.
2. **Browser extension captures** the selection.
3. The extension **sends the text** to the Spring Boot API.
4. API returns a **clean, concise summary**.
5. The extension **displays it in a popup**.

---
