# Arabic Voice AI Assistant

A browser-based Arabic voice assistant that uses speech recognition, Google Gemini AI, and text-to-speech to provide voice conversations.

---

## Project Overview

This project allows users to communicate with an AI assistant using their voice.

The browser converts speech into text, sends it securely to a PHP backend, which communicates with the Gemini API, then returns the response to the webpage. Finally, the browser reads the response aloud using Text-to-Speech.

---

## Features

- 🎤 Voice input
- 🤖 AI-generated responses using Google Gemini
- 🔊 Text-to-Speech
- 💬 Chat interface
- 📱 Responsive design
- 🔒 Secure API key storage using PHP

---

## Technologies Used

- HTML5
- CSS3
- JavaScript
- PHP
- Google Gemini API
- Web Speech API
- XAMPP (Local Server)

---

## How It Works

1. The user clicks the microphone button.
2. Speech Recognition converts speech into text.
3. JavaScript sends the text to the PHP backend.
4. PHP securely sends the request to the Gemini API.
5. Gemini generates a response.
6. The response appears in the chat.
7. The browser reads the response aloud.

---

## Problem Found

Initially, the chatbot displayed:

> "حدث خطأ أثناء الاتصال بالخادم"

The backend returned HTTP errors because of configuration issues while connecting to the Gemini API.

---

## Solution

The following issues were fixed:

- Fixed the PHP file path.
- Corrected the connection between JavaScript and PHP.
- Configured the API key correctly.
- Updated the API model to a supported Gemini model.
- Verified JSON responses from the backend.
- Tested the application on a local XAMPP server until it returned successful responses.

After these fixes, the chatbot successfully processed voice input and generated AI responses.

---

## Lessons Learned

Through this project I learned how to:

- Debug PHP applications
- Connect JavaScript with a backend API
- Handle JSON requests and responses
- Secure API keys
- Work with REST APIs
- Test projects using XAMPP
- Troubleshoot API errors

---

## Author

Developed as part of a practical training task.
