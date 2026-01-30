# VoiceCraft – Text to Speech Web App

A serverless Text-to-Speech web application built using AWS Polly, Lambda, API Gateway, and S3.

## Features
- Convert text into natural-sounding speech
- Serverless AWS architecture
- Browser-based audio playback
- Simple and clean UI

## Tech Stack
- Frontend: HTML, JavaScript
- Backend: AWS Lambda (Node.js)
- Cloud: AWS Polly, API Gateway, S3

## Architecture
Browser → API Gateway → Lambda → AWS Polly → Audio

## How to Run
1. Deploy Lambda function
2. Create API Gateway route
3. Update API URL in `frontend/script.js`
4. Host frontend using AWS S3 static hosting

## Future Enhancements
- Multiple voices & languages
- Download MP3
- React frontend
