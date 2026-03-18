🇶🇦 Sada Qatar (Echo of Qatar)
AI-Powered Oral History & Heritage Preservation System
Developed for Qatar National Vision 2030 - Social Development Pillar
📜 Project Overview
Sada Qatar is a specialized digital archiving system designed to preserve the intangible heritage of the State of Qatar. As the nation modernizes, the unique oral traditions, maritime songs (Fidjeri), and desert dialects of the elderly generation are at risk of being lost.
This system uses Artificial Intelligence to transcribe, translate, and categorize Qatari oral history, turning spoken memories into a searchable, bilingual national database.
✨ Key Features
Dialect-Aware Transcription: Uses OpenAI Whisper to accurately transcribe the Khaleeji/Qatari dialect from audio recordings.
Bilingual Archiving: Automatically translates Arabic transcripts into English for international research and cultural diplomacy.
AI Summarization: Generates instant recaps of long stories for quick browsing.
Heritage Gallery: A structured vault categorized by themes (Maritime, Desert Life, Poetry, etc.).
Impact Analytics: A data dashboard showing the progress of national preservation efforts.
🛠️ Technology Stack
Language: Python 3.12
Frontend: Streamlit (High-end Glassmorphism UI)
Speech-to-Text: OpenAI Whisper (Base Model)
Translation Engine: Deep-Translator (Google API integration)
Database: Pandas & CSV (Persistent local storage)
Infrastructure: GitHub Codespaces & Linux (Ubuntu)
Media Processing: FFmpeg (Backend audio engine)
🚀 Getting Started
1. Prerequisites
Ensure you have Python installed and the system-level audio processing engine (FFmpeg):
bash
sudo apt-get update && sudo apt-get install -y ffmpeg
Use code with caution.

2. Installation
Install the necessary Python libraries:
bash
pip install streamlit openai-whisper deep-translator pandas
Use code with caution.

3. Running the Application
Navigate to the project directory and launch the Streamlit server:
bash
streamlit run app.py
Use code with caution.

📈 Vision 2030 Alignment
This project directly addresses the Social Development pillar of the Qatar National Vision 2030:
Preservation of National Heritage: Safeguarding Qatari identity in a globalized world.
Knowledge-Based Economy: Using advanced AI to manage national cultural assets.
Cultural Exchange: Making Qatari history accessible to the global community in multiple languages.
Developer Note: Built individually as a proof-of-concept for the Ministry of Culture to demonstrate the power of AI in heritage preservation.
