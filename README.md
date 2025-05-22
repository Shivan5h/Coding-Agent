# 🚀 Custom Code Generation & Execution Agent using LangChain

This project demonstrates an AI-powered code assistant that can generate **complete, runnable programs** from natural language prompts and execute them instantly in **Python, Java, or C++**.

## 🧠 AI Model Name & Type

- **Model Type**: Large Language Model (LLM) with LangChain agent
- **Tools Used**: `LangChain`, `OpenAI API`, `PythonREPL`, `Streamlit`, `subprocess`

---

## 🎯 Objective

The goal is to build a user-friendly system that:
- Understands coding prompts.
- Generates fully functional source code.
- Executes it in real-time.
- Returns the output to the user instantly.

Larger aim: Automate development, learning, and debugging for software developers, students, and educators.

---

## 📦 Dataset

No pre-built dataset is used. The system relies on **real-time user prompts** as input data.

---

## 🔧 Model Development

- **Framework**: Streamlit for UI
- **Code Execution**: subprocess for Java & C++, `exec()` for Python
- **LangChain Agent**: Configured with OpenAI LLM & Python REPL tool
- **Supported Languages**: Python, Java, C++

---

## ⚠️ Challenges & Solutions

- **Prompt Engineering**: Ensured code includes imports, `main` methods, test cases, and explanations.
- **Cross-Language Execution**: Designed separate logic for compiling and executing Java and C++ safely.
- **Security**: Restricted execution scope, captured exceptions, and isolated execution for safety.

---

## 🌍 Impact

- Reduces time for prototype development.
- Helps beginners understand code structures and logic.
- Promotes rapid learning and experimentation.
- Can serve as a coding tutor or assistant.

---

## 📈 Scalability

This system can be scaled to:
- Education platforms
- Developer productivity tools
- Low-code/no-code platforms
- Coding interview assistants

---

## 💡 Interest Area

**Corporate AI** – Aimed at developer productivity and smart assistants.

---

## ▶️ Demo Instructions

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
