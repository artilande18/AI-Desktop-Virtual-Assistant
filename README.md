# 🤖 AI Desktop Virtual Assistant
An AI-powered Desktop Virtual Assistant built using Python that can understand voice commands, perform tasks, and respond using speech output. This project integrates Speech Recognition, Text-to-Speech, Web Automation, and GUI development.

## Project Overview
The AI Desktop Virtual Assistant is a Python-based application that allows users to interact with their computer using voice or text commands. It processes user input, performs specific actions such as opening websites, telling the current time, fetching weather updates, and responds through voice output.
This project demonstrates practical implementation of Artificial Intelligence concepts, automation, and desktop application development.

## Features
-  Speech-to-Text (Voice Command Recognition)
-  Text-to-Speech (Voice Response)
-  Open Websites (YouTube, Google, etc.)
-  Real-time Clock Information
-  Weather Information Fetching
-  GUI Interface using Tkinter
-  Text-based Command Support
-  Application Shutdown via Voice Command

## Technologies Used
- Python
- Tkinter (GUI Development)
- speech_recognition (Voice Input)
- pyttsx3 (Text-to-Speech)
- requests_html (Web Scraping)
- webbrowser (Browser Automation)
- datetime (Time Handling)
- PIL (Image Handling)

## System Architecture
User Voice/Text  
        ↓  
Speech Recognition Module  
        ↓  
Action Processing Module  
        ↓  
Task Execution (Web/Time/Weather)  
        ↓  
Text Response  
        ↓  
Text-to-Speech Output  
