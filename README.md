
# Streamlit Interview Chatbot

A conversational HR interview simulation app built with Streamlit and OpenAI's API. This chatbot collects user details, simulates an AI-driven interview based on the provided information, and generates performance feedback.

## 🚀 Features

- Interactive setup form to collect:
  - Name
  - Experience
  - Skills
  - Desired job position, company, and level
- AI-powered interview with up to 5 user responses
- Feedback generator with a performance score and detailed comments
- Option to restart the interview

## 🧠 Powered By

- [Streamlit](https://streamlit.io/) for the user interface
- [OpenAI GPT-4o](https://openai.com/) for generating interview questions and feedback
- [streamlit-js-eval](https://pypi.org/project/streamlit-js-eval/) for dynamic page reloads

## 📦 Requirements

- Python 3.8+
- OpenAI API key

Install dependencies:

```bash
pip install streamlit openai streamlit-js-eval
```

## 🔐 Secrets Configuration

Create a `.streamlit/secrets.toml` file and add your OpenAI API key:

```toml
[general]
OPENAI_API_KEY = "your_openai_api_key"
```

## ▶️ Running the App

```bash
streamlit run app.py
```

## 📋 Notes

- Maximum of 5 user responses per interview session.
- Feedback is generated only once after the conversation ends.
- You can restart the process using the **Restart Interview** button.

## 📸 Screenshots

![App Screenshot](screenshot.png)

## 🛠️ Future Improvements

- Add persistent session storage
- Allow downloading feedback as PDF
- Integrate voice input/output for accessibility

---

© 2025 Your Name or Company
