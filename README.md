# RecruitIQ - 📄AI Powered Resume Screening System

An AI-powered Resume Screening System that automates candidate shortlisting by analyzing and matching resumes with job descriptions using Natural Language Processing (NLP).



🚀 Features

📂 Upload multiple resumes (PDF/DOCX)
📝 Input job description
🔍 Extract key information (skills, education, experience)
📊 Rank candidates based on relevance
🤖 NLP-based semantic matching
⚡ Fast and efficient screening process



🧠 Tech Stack

Python
NLP Libraries: Scikit-learn, NLTK
Optional: BERT for advanced matching
Web Framework: Flask / Streamlit
File Handling: PyMuPDF, docx


⚙️ How It Works

Upload resumes and provide a job description
Text is preprocessed (tokenization, stopword removal, etc.)
Features are extracted using TF-IDF
Cosine similarity is calculated between resumes and job description
Candidates are ranked based on similarity score




📁 Project Structure

resume-screening-system/
│── data/                 # Sample resumes and job descriptions
│── models/               # Saved ML models
│── app.py                # Main application
│── utils.py              # Helper functions
│── requirements.txt      # Dependencies
│── README.md             # Project documentation
🛠️ Installation





▶️ Usage

# Run the application
python app.py

Then open your browser and upload resumes + job description to see ranked results.

📊 Example Output

Candidate A → 85% match
Candidate B → 72% match
Candidate C → 60% match



💡 Future Improvements

Add deep learning models for better semantic understanding
Integrate database for storing resumes
Build a full-stack web dashboard
Add skill gap analysis


🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.


👨‍💻 Author

SAKSHAM DAVE 
GitHub: https://github.com/your-username
