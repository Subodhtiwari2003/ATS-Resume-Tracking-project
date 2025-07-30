# ATS-Resume-Tracking_Project

A smart, AI-powered tool that mimics Applicant Tracking Systems (ATS) by analyzing resumes for relevance and formatting using natural language models. Built using Python, Streamlit, and the Gemini Pro API.

## 🚀 Features

- 📄 **PDF Resume Parsing** – Extracts text directly from uploaded resumes.
- 🧠 **AI-Powered Scoring** – Uses Google's Gemini API to evaluate resumes against job descriptions.
- 🌐 **Interactive UI** – Streamlit-powered interface for seamless user experience.
- 📊 **Content Feedback** – Returns summarized AI feedback and alignment tips.

## 🛠️ Tech Stack

| Component       | Description                         |
|----------------|-------------------------------------|
| Python 3.12     | Core programming language           |
| Streamlit       | Front-end interface                 |
| Gemini API      | Resume content generation & scoring |
| PyPDF2          | PDF text extraction                 |
| Anaconda        | Environment & dependency management |

## 📁 Project Structure
## ⚙️ How to Run
```bash
# Create environment
conda create -n test python=3.12 -y
conda activate test

# Install dependencies
pip install -r requirements.txt

# Launch the app
streamlit run app.py

## Example Prompt Usag
response = model.generate_content(
  f"Rate this resume against the job role of 'Junior Data Scientist'.\n\nResume:\n{text}"
)

# Purpose






