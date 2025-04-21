
# Streamlit HR Interview Bot

This Streamlit app simulates an HR interview experience using OpenAI's GPT-4o. It gathers the user's profile information and conducts a chatbot-based interview tailored to the selected job position.

## 🎯 Features

- Personal profile setup (name, experience, and skills)
- Job preference selection (level, position, and company)
- Streamlit UI with setup and interview phases
- GPT-powered interview responses
- Session-based chat memory

## 🧠 Powered By

- [Streamlit](https://streamlit.io/) for frontend UI
- [OpenAI GPT-4o](https://openai.com/) for dynamic, context-aware interviewing

## 📦 Requirements

- Python 3.8+
- OpenAI API key

Install dependencies:

```bash
pip install streamlit openai
```

## 🔐 Secrets Configuration

Create a `.streamlit/secrets.toml` file and include your OpenAI API key:

```toml
[general]
OPENAI_API_KEY = "your_openai_api_key"
```

## ▶️ Running the App

```bash
streamlit run app3.py
```

## 💬 Flow

1. Fill out personal and job preference information.
2. Click “Start Interview” to begin the chatbot session.
3. Chat with the AI for an interactive, position-specific interview experience.

---

© 2025 Your Name or Company
