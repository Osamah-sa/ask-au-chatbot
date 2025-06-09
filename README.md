# Ask AU – AI Chatbot

A smart and user-friendly desktop chatbot built with Python to assist students with quick answers to common university questions. The chatbot combines local FAQ search with GPT-4 AI integration for flexible and intelligent responses.

---

## Project Overview

Ask AU is a desktop-based AI chatbot designed to improve access to information for students and visitors. It answers common questions about course registration, application processes, exam policies, and more — either from a local database or by generating intelligent answers using the OpenAI API.

---

## Features

-  Searches local FAQ data using fuzzy matching
-  Uses OpenAI GPT-4 for complex or unknown queries
-  Simple GUI with quick-question buttons
-  Typing simulation and clickable URLs
-  Secure API key management with `.env` file
-  No installation required — runs as `.py` or compiled `.exe`

---

## Technologies Used

- **Python**
- **Tkinter** & **ttkbootstrap** for GUI
- **OpenAI GPT API**
- **RapidFuzz** for fuzzy string matching
- **dotenv** for secure environment variable handling
- **webbrowser**, **threading**, **json**

---

## Getting Started

1. Clone or download the repository
2. Add your OpenAI API key to a `.env` file:
3. 3. Run the chatbot:
- `python chatbot.py` 
- or open `chatbot.exe`

---

## Important Notes


- This project was originally inspired by real university FAQ content but rewritten for public demonstration

---

## License

This project is released for educational and demonstration purposes only.


