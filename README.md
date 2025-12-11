
🚀 AI Powered Resume Screening Tool

An AI-driven application that automatically evaluates resumes, extracts important information, and scores them based on job-specific requirements using NLP and Machine Learning.

📌 Overview

This tool streamlines the recruitment process by analyzing resumes and ranking candidates using intelligent text processing. It reduces manual screening workload and improves the efficiency of selecting the right candidates.

The system extracts:
✔ Skills
✔ Experience
✔ Education
✔ Achievements
✔ Relevant keywords

And compares them against a job description to produce a compatibility score.

🧠 Key Features
	•	Resume Parsing using NLP
	•	Keyword & Skill Extraction
	•	Job Description Matching
	•	Automated Resume Scoring
	•	User-friendly Web Interface
	•	Flask-based API Backend
	•	Custom ML/NLP pipelines for processing text
	
🛠 Tech Stack
AI / NLP
	•	Scikit-learn
	•	NLTK / spaCy
	•	TF-IDF Vectorizer
	•	Cosine Similarity

Backend
	•	Python
	•	Flask

Frontend
	•	HTML / CSS / JS

Others
	•	Git, GitHub
	•	Pandas, NumPy
	
📂 Project Structure

AI-Powered-Resume-Screening-Tool/
│
├── app.py                 # Flask backend
├── static/                # CSS, JS
├── templates/             # HTML files
├── models/                # Saved vectorizers / ML models
├── utils/                 # Preprocessing scripts
└── README.md
⚙️ How It Works

1. Preprocessing

Resumes are cleaned using NLP techniques:
	•	Removing punctuation
	•	Lemmatization
	•	Stopword removal
	•	Lowercasing

2. Feature Extraction

TF-IDF converts resume text and job descriptions into vector embeddings.

3. Similarity Scoring

Cosine similarity computes how closely a resume matches the job requirements.

4. Ranking

Resumes are sorted by total match score.

🚀 How to Run This Project Locally

1. Install dependencies

pip install -r requirements.txt

2. Start Flask server

python app.py

3. Open browser

http://127.0.0.1:5000

Upload a resume → Get extracted skills, score, and match percentage.

📑 Use Cases
	•	HR teams for fast screening
	•	Startups hiring multiple candidates
	•	ATS integration
	•	Resume evaluation for training institutes

🧪 Model & NLP Pipeline

The ML pipeline includes:
	•	TF-IDF Vectorization
	•	Similarity Scoring
	•	Keyword Extraction
	•	Rule-based prioritization

Optionally, advanced models like BERT can be integrated.

📈 Future Enhancements
	•	Add BERT-based semantic similarity
	•	Support for multiple languages
	•	JD auto-parsing and auto-skill extraction
	•	Cloud deployment (AWS/GCP)
	•	Dashboard for analytics

👨‍💻 Author

MD RUHAAN
Software Engineer

🤝 Contributions

Pull requests are welcome.
For major changes, please open an issue first.

