# ResuMate AI — Smart Resume Analyzer & Job Fit Recommender

🎯 AI-based tool to analyze resumes, match them with job descriptions, and provide smart recommendations to improve hiring success.

## 🔧 Features
- Resume parsing (PDF, DOCX)
- JD comparison using NLP
- Job fit scoring
- Visual feedback and keyword suggestions
- Resume improvement tips

## 🧠 Tech Stack
- Python, Flask / FastAPI
- NLP: spaCy, SBERT, NLTK
- ML: scikit-learn
- Frontend: Streamlit or React
- Deployment: Docker, AWS / Heroku

📊 Sample Output

Job Fit Score: 86%

Missing Skills: ['TensorFlow', 'ETL']

Suggested Improvements: Add recent projects using NLP, etc.

## 🚀 Running Locally
```bash
git clone https://github.com/YourUsername/ResuMate-AI.git
cd ResuMate-AI
pip install -r requirements.txt
python backend/app.py
