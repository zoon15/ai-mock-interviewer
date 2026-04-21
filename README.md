
# 🎤 AI Mock Interviewer

An AI-powered mock interview web app built with Python and Mistral AI.
Practice your interview skills anytime, for any job role — completely free!

## 💡 What it does
- Enter any job role (e.g. Software Engineer, Marketing Manager)
- AI conducts a realistic 5-question mock interview
- Questions get progressively harder
- Receive structured feedback at the end with Strengths, Areas to Improve, and 3 Tips

## 🛠️ Tech Stack
- Python 3
- Mistral AI API (LLM)
- Flask (coming Day 5)
- HTML/CSS (coming Day 5)

## 🚀 How to run

1. Clone the repo
git clone https://github.com/zoon15/ai-mock-interviewer.git

2. Go into the folder
cd ai-mock-interviewer

3. Activate virtual environment
source venv/bin/activate

4. Install dependencies
pip install -r requirements.txt

5. Add your Mistral API key in interviewer.py

6. Run the app
python3 interviewer.py

7. Enter a job role and start practicing!

## ✅ Features built so far
- Role-specific interview questions
- 5 question interview flow
- Input validation and error handling
- Retry logic for API failures
- Response time tracking
- Safety guardrails against prompt injection

## 🔒 Security
- API keys stored in .env file (not committed to GitHub)
- Input validation on all user inputs
- Prompt injection protection

## 📅 Built as part of AI Application Building Challenge 2026