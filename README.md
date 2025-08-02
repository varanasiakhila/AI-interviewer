
 #  Emotion Based AI-Interviewer
An interactive tool that helps users practice interviews by analyzing resumes, generating personalized questions, simulating a voice-based interviewer, and giving emotion-based feedback from video responses.
+
 # 📝 Description 
This AI-powered tool helps users prepare for interviews by simulating a real interview experience. It extracts skills from uploaded resumes (PDF/DOCX), generates customized technical and HR questions, and uses text-to-speech to ask them aloud. Users upload a video of their responses, and the system gives feedback based on simulated emotion analysis to improve communication and confidence.
+
 # 🚀 Key Features
- 🔍Resume Parsing: Extracts skills from PDF/DOCX using spaCy NLP
- 🗣TTS Interview Questions: Asks tailored technical & HR questions via gTTS
- 🎤Video Upload: Users upload interview responses for review
- 📊Emotion Feedback: Simulates emotional analysis (happy, fear, neutral, etc.)
- Smart Tips: Suggests improvements based on emotional expression

 # 🧠 Technologies Used
| Feature                | Tools / Libraries                |
|------------------------|----------------------------------|
| Resume Parsing         | pdfplumber, docx2txt, spaCy |
| Question Generation    | random, spaCy NLP            |
| Audio Playback         | gTTS (Google TTS)              |
| Emotion Simulation     | random, optionally FER       |
| Video Handling & UI    | OpenCV, Gradio               |
| Session Management     | Python global dictionary         |





