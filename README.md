Tamil Voice & Text Chatbot (Offline)
Project Overview
This project is a simple Tamil voice and text chatbot designed to function even without an internet connection (offline). Users can interact with the chatbot using either voice or text input, and the chatbot will provide responses in Tamil, both in voice and text format.

Features
Full Offline Functionality: Utilizes a Service Worker to enable the chatbot to operate even when there is no internet connection.
Voice Input (Speech to Text - STT): Users can ask questions in Tamil using their voice (via the Web Speech Recognition API).
Voice Output (Text to Speech - TTS): The chatbot will speak its responses in Tamil (via the Web Speech Synthesis API).
Text Input: Users can also type their questions.
Simple Rule-Based Responses: Provides basic answers to common Tamil questions (e.g., greetings, name, time, date, capital of Tamil Nadu, Indian independence year).
User-Friendly Interface: A simple and clean chat interface.
Technologies Used
HTML: For the structure and content of the chatbot.
CSS: For styling the user interface.
JavaScript:
Web Speech API: For Speech to Text (voice recognition) and Text to Speech (voice synthesis) functionalities.
Service Workers: To enable offline operation.
Basic Logic: Simple rule-based processing to understand user inputs and generate responses.
How to Run
Save this my personal ai.html file on your computer.
Create a separate JavaScript file named service-worker.js in the same directory. This HTML file expects the service-worker.js file to be registered.
Open the my personal ai.html file in a modern web browser (e.g., Google Chrome, Microsoft Edge).
