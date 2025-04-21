
# Streamlit Interview Setup Chatbot

An interactive Streamlit app that simulates an HR interview process using OpenAI's GPT-4o. It collects personal and professional details, then initiates a chatbot-style interview tailored to the user’s profile.

## 🎯 Features

- Collects personal details: name, experience, and skills
- Selects job-related preferences: level, position, and company
- Personalized HR-style interview with AI responses
- Real-time response streaming
- Session-based conversation memory

## 🧠 Powered By

- [Streamlit](https://streamlit.io/) for building the web UI
- [OpenAI GPT-4o](https://openai.com/) for intelligent interview responses

## 📦 Requirements

- Python 3.8+
- OpenAI API key

Install dependencies:

```bash
pip install streamlit openai
```

## 🔐 Secrets Configuration

Create a `.streamlit/secrets.toml` file and insert your OpenAI API key:

```toml
[general]
OPENAI_API_KEY = "your_openai_api_key"
```

## ▶️ Running the App

```bash
streamlit run app2.py
```

## 💬 Example Flow

1. Enter your name, experience, and skills.
2. Choose your level, position, and company.
3. Engage in a personalized mock interview.
4. Enjoy real-time AI responses tailored to your background.

---

© 2025 Your Name or Company
