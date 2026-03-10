Overview

The TatvAI is an AI-powered web platform designed to analyze news articles and videos using multimodal intelligence. It helps users quickly understand lengthy content by generating concise summaries, detecting fake news, and providing AI-driven future predictions. The system promotes reliable information consumption through credibility analysis, multilingual access, and an interactive dashboard.

Features

User-Friendly Interface: Clean and responsive dashboard for seamless navigation
Multimodal Summarization: Generates summaries from both video and text content
Speech-to-Text Transcription: Converts video audio into text using Whisper AI
Fake News Detection: Identifies misleading content using BERT-based classification
AI Predictions: Provides future insights based on analyzed news topics
Multilingual Support: Translates summaries into multiple regional languages
Real-Time Processing: Fast backend pipelines for instant results
Bookmark & Accessibility: Save articles and listen to summaries via text-to-speech

Technologies Used
Backend

Python Flask – REST API development
HuggingFace Transformers – Summarization & NLP models
OpenAI Whisper – Speech-to-text transcription
BERT Model – Fake news detection
Gemini / LLM APIs – AI-based predictions
Translation APIs – Multilingual support

Frontend

HTML, CSS, JavaScript – Structure and interactivity
Node.js & Express – Server-side integration
Google Maps API (optional) – Location-based news features
Responsive UI Design – Mobile and desktop compatibility

Project Structure
├── frontend/               # User interface files
│   ├── index.html
│   ├── styles.css
│   └── app.js
│
├── backend/                # AI processing server
│   ├── ai_server.py
│   ├── summarizer.py
│   ├── fake_news_model.py
│   └── prediction_engine.py
│
└── assets/ (optional)      # Icons, images, UI resources
How to Use
Clone the repository
git clone https://github.com/your-username/tatvai
cd tatvai
Install dependencies
pip install -r requirements.txt
npm install
Run the servers
python ai_server.py
npm start
Use the app

Open http://localhost:3000 in your browser
Upload a video or select a news article
View AI summary, credibility score, predictions, and translated content

Use Case

A student wants to understand a long news analysis video quickly.
They upload the video to TatvAI.
The system extracts keyframes, transcribes audio, generates a concise summary, detects misinformation, and provides future predictions.
The student can also translate the summary into their preferred language and listen to it via text-to-speech.

🧪 License

This project is developed for academic, research, and social good purposes. AI models and third-party APIs are subject to their respective licenses.
