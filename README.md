# AI-Driven-Resume-Evaluator
An AI-powered web app to evaluate resumes and provide career recommendations using NLP and data analytics.
An intelligent web application built with Streamlit that analyzes resumes using NLP techniques, provides skill-based recommendations, predicts career fields, and offers personalized courses & interview preparation resources.

Features
Resume Parsing: Extracts personal info, skills, education, and experience from uploaded resumes (PDF).

Candidate Level Prediction: Classifies user as Fresher, Intermediate, or Experienced.

Skills Recommendation: Suggests essential skills to enhance resume quality.

Course & Certification Suggestions: Recommends relevant online courses for upskilling.

Resume Scoring & Tips: Evaluates resume quality and gives improvement suggestions.

Admin Dashboard (Optional): Visual analytics on user data & feedback for administrators.

Tech Stack
Frontend & Backend: Streamlit

Programming Language: Python

NLP Libraries: Spacy, PDFMiner, PyResparser

Visualization: Plotly, Pandas

Database: MySQL (for user data & feedback)

Others: Geopy, Pymysql, Streamlit-Tags

Project Structure
bash
Copy code
.
├── App.py                  # Main Streamlit app script
├── requirements.txt        # Project dependencies
├── Logo/                   # App logos and images
├── Uploaded_Resumes/       # Folder to save uploaded resumes
├── Courses.py              # Predefined course recommendations
└── README.md               # Project documentation
How to Run Locally
Clone the repository:

bash
Copy code
git clone https://github.com/YourUsername/AI-Driven-Resume-Evaluator.git
cd AI-Driven-Resume-Evaluator
(Optional) Create a virtual environment:

bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Streamlit app:

bash
Copy code
streamlit run App.py
Open http://localhost:8501 in your browser.

Research Paper
This project is published in IJIRCEE (International Journal of Innovative Research in Computer and Communication Engineering).
Link to Paper (if available)

Credits
Developed by Debasish Nayak

License
This project is licensed under the MIT License.
