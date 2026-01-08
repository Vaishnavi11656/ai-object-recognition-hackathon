# AI-Based Object Recognition Web Application (Hackathon Project)

This project was developed as part of a hackathon. The application captures objects using a device camera and provides meaningful information in both text and audio formats.

## Problem Statement
Build a web application that recognizes an object placed in front of a camera and provides meaningful information about that object in both text and audio formats.

## Features
- Accesses the device camera to capture objects
- Captures images using live camera feed
- Sends the captured image to an external AI service (Gemini Vision API)
- Displays object details in readable text format
- Plays the same information as audio using Text-to-Speech
- Ensures synchronization between displayed text and audio output
- Clean and beginner-friendly user interface

## Tech Stack
- React.js
- JavaScript
- HTML, CSS
- Gemini AI API
- Web Speech API
- Vite

## User Flow
1. User opens the application
2. User allows camera access
3. User places an object in front of the camera
4. Application captures the object
5. AI analyzes the image
6. Object details are displayed as text
7. The same details are played as voice output

## How to Run the Project
```bash
npm install
npm run dev
