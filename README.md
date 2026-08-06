# 🚀 GenAI Applications using LangChain, LangServe, FastAPI & Streamlit

> A collection of beginner-friendly **Generative AI applications** built using **LangChain**, **LangServe**, **FastAPI**, and **Streamlit**.

This repository demonstrates how to build and deploy AI-powered applications using Large Language Models (LLMs). Each project showcases the integration of **LangChain** for orchestration, **LangServe** for serving chains as APIs, **FastAPI** as the backend framework, and **Streamlit** for creating interactive user interfaces.

---

## 📌 Projects Included

### 🌍 1. Language Translator

A multilingual translation application that translates text from one language to another using an LLM.

#### ✨ Features

* Translate text between multiple languages
* Example: French ➜ English
* User-friendly Streamlit interface
* FastAPI backend
* LangServe API endpoints
* Prompt Templates using LangChain
* Easy to customize for additional languages

#### 🛠 Tech Stack

* Python
* LangChain
* LangServe
* FastAPI
* Streamlit

---

### 🤖 2. AI Chatbot

A conversational AI chatbot capable of answering user questions in natural language.

#### ✨ Features

* Interactive chat interface
* Intelligent question answering
* Clean Streamlit UI
* FastAPI backend
* LangServe integration
* Built using LangChain

#### 🛠 Tech Stack

* Python
* LangChain
* LangServe
* FastAPI
* Streamlit

---

# 🏗️ Project Architecture

```text
                    User
                      │
              Streamlit Frontend
                      │
                      ▼
                FastAPI Backend
                      │
                 LangServe APIs
                      │
                      ▼
                 LangChain Chain
                      │
                      ▼
             Large Language Model
                      │
                      ▼
                   Response
```

---

# 📂 Project Structure

```text
GenAI-Projects/
│
├── Language-Translator/
│   ├── app.py
│   ├── client.py
│   ├── requirements.txt
│   └── README.md
│
├── ChatBot/
│   ├── app.py
│   ├── client.py
│   ├── requirements.txt
│   └── README.md
│
└── README.md
```

---

# ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/GenAI-Projects.git
```

Navigate to the project

```bash
cd GenAI-Projects
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Run the FastAPI Server

```bash
python server.py
```

or

```bash
uvicorn app:app --reload
```

---

# ▶️ Run the Streamlit Application

```bash
streamlit run app.py
```

---

# 🧰 Technologies Used

* 🐍 Python
* 🦜 LangChain
* 🚀 LangServe
* ⚡ FastAPI
* 🎨 Streamlit
* 🤖 Large Language Models (LLMs)

---

# 📚 What You'll Learn

* Building Generative AI applications
* Creating APIs using FastAPI
* Serving LangChain applications with LangServe
* Prompt Engineering
* Building interactive Streamlit applications
* Connecting frontend and backend
* Developing production-ready AI applications

---

# 🚀 Future Improvements

* ✅ Conversation Memory
* ✅ Multiple LLM Support
* ✅ RAG (Retrieval-Augmented Generation)
* ✅ PDF Chat
* ✅ Document Summarization
* ✅ Voice Assistant
* ✅ Authentication
* ✅ Docker Deployment
* ✅ Cloud Deployment (Azure / AWS / GCP)

---

# 🤝 Contributing

Contributions, issues, and feature requests are welcome!

If you'd like to improve this project, feel free to fork the repository and submit a pull request.

---

# ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.

It motivates me to continue building more AI and Generative AI projects for the community.
