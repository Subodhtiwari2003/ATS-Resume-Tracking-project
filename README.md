## ATS Resume Tracking Project
An intelligent, AI-driven web app that simulates how Applicant Tracking Systems (ATS) evaluate resumes—so candidates can stay ahead of the job hunt. Built with Python, Streamlit, and Google’s Gemini Pro API.

## What It Does
This tool empowers job seekers to:
- 📄 Upload their resume in PDF format
- 🧠 Get instant AI-based scoring for job relevance
- 📊 Receive personalized feedback to optimize resume conten
- 🌐 Interact through a clean, responsive Streamlit-powered U

##  Key Features
 Key Features
| ⚙️ Feature | 💡 Description | 
| PDF Resume Parsing | Extracts raw text from uploaded PDFs using PyPDF2 | 
| Gemini Pro API Scoring | Evaluates resume strength based on job description with LLM-generated insights | 
| Interactive UI | Streamlit frontend makes resume evaluation seamless and intuitive | 
| AI Feedback Summary | Highlights strengths, weaknesses, and ATS compatibility tips | 

## Tech Stack
 Tech Stack
| 🔧 Component | 📘 Purpose | 
| Python 3.12 | Base language for logic and integration |
 | Streamlit | UI interface for resume scoring dashboard | 
| Gemini API | AI-powered resume evaluation and feedback | 
| PyPDF2 | Extracts content from uploaded resume PDFs | 
| Anaconda | Manages environment setup and dependencies | 

## Project Structure
├── app.py                  # Streamlit app logic
├── requirements.txt        # Python packages needed
├── LICENSE                 # Project licensing (GPL-3.0)
├── .gitignore              # Git exclusions

## Getting Started
To run this project locally:
# Create and activate environment
conda create -n ats-resume-env python=3.12 -y
conda activate ats-resume-env

# Install required packages
pip install -r requirements.txt

# Start the app
streamlit run app.py

## Purpose
 This project helps candidates:
- Test their resumes against AI-powered benchmarks.
- Optimize resumes for better ATS compatibility.
- Gain constructive feedback before applying for jobs.






















