# 🎯 ResuMatch — AI Resume & Job Matcher

**ResuMatch** is an intelligent career assistant that parses technical resumes, detects your core skills and primary tech roles, evaluates skill gaps, and matches you with real-time job openings and salary insights across 30+ countries.

---

## ✨ Features

- 📄 **Resume Skill Extraction**: Parses keywords across 100+ modern tech stacks and tools.
- 🎯 **Role & Fit Detection**: Evaluates match confidence across multiple engineering & data domains.
- 📊 **Skill Gap & Roadmap**: Identifies missing skills and generates tailored learning roadmaps.
- 🌍 **Global Job Board Matching**: Integrates job searches with regional boards across Asia, Europe, North America, Oceania, and more.
- 💰 **Salary Insights**: Provides localized market benchmarks by seniority level.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask, Flask-CORS, Gunicorn
- **Frontend**: HTML5, CSS3, JavaScript (Jinja Templates)
- **Deployment**: Render / PaaS ready

---

## 🚀 Run Locally

```bash
# Clone repository
git clone https://github.com/amirtha-varshine/ResuMatch.git
cd ResuMatch

# Set up virtual environment
python -m venv .venv
.venv\Scripts\activate      # On Windows
# source .venv/bin/activate # On macOS/Linux

# Install dependencies
pip install -r requirements.txt

# Run app
python app.py
```

Visit `http://localhost:5000` in your browser.
