SparshVoice is a rural-friendly, AI-powered Sign Language Translator designed to enable seamless two-way communication between deaf/hard-of-hearing individuals and non-signers.The system translates Indian Sign Language (ISL) gestures into text and voice, and converts spoken words back into sign animations, enabling real-time inclusive communication in healthcare, government services, and public institutions.
Built using a scalable, serverless AWS architecture.

Problem Statement

Millions of deaf and hard-of-hearing individuals in India face daily communication barriers due to limited awareness of Indian Sign Language (ISL). 
In hospitals, rural clinics, and public service centers, the absence of interpreters leads to misunderstandings and delays in critical services.
SparshVoice addresses this gap with an AI-powered, low-cost, scalable communication solution.

Target Users

Deaf and hard-of-hearing individuals
Doctors & hospital staff
Government service providers
Rural healthcare centers
Schools & public institutions

Proposed Solution

SparshVoice enables:
🖐 Sign → Text/Voice translation
🎤 Voice/Text → Sign animation
🏥 Hospital Mode with emergency quick phrases
🌐 Hindi & English multilingual output
📱 Rural-first, accessible design

Key Features

🔄 Real-time bidirectional communication
⚡ Low-latency AI inference
🚑 Emergency quick-response mode
🌍 Multilingual speech output
☁️ Fully serverless cloud architecture
📊 Scalable and deployment-ready

Technology Stack
🌐 Frontend

React.js
HTML5 / CSS3
JavaScript
Web Camera API
Web Speech API

⚡ Backend (Serverless)
AWS Lambda
Amazon API Gateway

🤖 AI / ML

Amazon Rekognition / SageMaker (Gesture Recognition)
Amazon Lex (Speech-to-Text)
Amazon Polly (Text-to-Speech)
Amazon Translate (Multilingual Support)

💾 Storage & Monitoring
Amazon S3
Amazon CloudWatch

Architecture Overview

Frontend (React App)
Amazon API Gateway
AWS Lambda
Rekognition / SageMaker / Lex / Polly / Translate
Amazon S3 (Storage)
Fully serverless for scalability and cost efficiency.

Use Case: Healthcare Sector

In hospitals and rural clinics, SparshVoice enables doctors and deaf patients to communicate instantly without the need for interpreters.
Emergency Mode ensures quick access to life-saving phrases such as:
"I am in pain"
"Call a doctor"
"I need medicine"
This improves diagnosis accuracy, reduces response time, and enhances patient dignity.

Future Enhancements

Edge AI for offline gesture detection
3D animated sign avatar

Expanded ISL dataset

Deployment across government hospitals
Integration with telemedicine platforms

Expected Impact

Promotes digital inclusion
Improves healthcare accessibility
Reduces communication barriers
Scalable across rural and urban India
