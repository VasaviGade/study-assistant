# 🤖 Study Assistant

An AI-powered study assistant that provides beginner-friendly explanations using Google Gemini.

## ✨ Features

- Ask questions and get AI-generated explanations
- Friendly personality mode
- Academic personality mode
- Uses analogies and real-world examples
- Interactive Gradio interface

## 🛠️ Technologies Used

- Python
- Google Gemini API
- Gradio
- GitHub
- Render

## 🚀 How It Works

The user enters a question and selects a personality.

The application sends the question to the Gemini API along with the selected personality instructions and displays the generated explanation.

## 🔐 Environment Variable

The Gemini API key is stored securely as an environment variable:

```text
GEMINI_API_KEY

🌐 Live Demo
https://study-assistant-9c6j.onrender.com

📂 Project Structure
study-assistant/
│
├── app.py
├── requirements.txt
└── README.md

md
📚 What I Learned
1.Integrating an AI API with Python
2.Creating an interactive interface using Gradio
3.Managing API keys using environment variables
4.Deploying a Python AI application using Render
5.Using GitHub to manage project code
