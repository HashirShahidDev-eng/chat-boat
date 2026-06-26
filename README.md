# chat-boat
# 🩺 General Health Query Chatbot

## Task Objective
Develop an AI chatbot that answers general health questions in simple language while avoiding diagnosis and medicine prescriptions.

## Dataset Used
No custom dataset was used. The chatbot uses a pre-trained Large Language Model (LLM) through an API.

## AI Models Applied
- Hugging Face: `mistralai/Mistral-7B-Instruct-v0.1` (initially tried but failed due to DNS/API connection issues).
- Groq API: `llama-3.3-70b-versatile` (final model used because it provided reliable and faster responses).
## Key Results and Findings
- Created a working health chatbot.
- Provides general health information safely.
- Added restrictions for harmful queries.
- Maintains conversation history.
- Groq API worked successfully after Hugging Face failed.

## Technologies Used
Python, Groq API, Llama 3.3 70B Model
