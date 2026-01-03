# AI-Powered Resume Evaluation & ATS Scoring System

An end-to-end AI-driven workflow that evaluates resumes against job descriptions using semantic analysis instead of keyword matching. Built using **n8n** and **Google Gemini**, this system automates resume parsing, skill matching, gap analysis, relevance scoring, and structured output storage.

---

## 🚀 Project Overview

Traditional ATS systems rely heavily on rigid keyword filters, often missing strong candidates.  
This project takes a **recruiter-first, AI-driven approach**, mimicking how humans evaluate resumes.

### What it does:
- Parses resume and job description PDFs
- Uses Gemini to perform semantic evaluation
- Matches skills and identifies missing competencies
- Generates an explainable relevance score
- Automatically updates results in Google Sheets

---

## 🧠 How It Works

1. **Resume Upload**
   - Resumes are uploaded via Google Drive
2. **PDF Parsing**
   - Resume and JD text extracted automatically
3. **AI Evaluation**
   - Gemini analyzes resume against JD contextually
4. **Structured Output**
   - Name, contact info, score, skills, gaps extracted
5. **Automation**
   - Results are logged into Google Sheets for easy review

---

## 🔄 Workflow Architecture
Google Drive Trigger
↓
Download Resume PDF
↓
Extract Resume Text
↓
Extract Job Description Text
↓
Gemini AI Evaluation
↓
Structured Data Mapping
↓
Google Sheets Update


---

## 📊 Output Fields

- Candidate Name
- Email & Phone Number
- Relevance Score (0–100)
- Explanation of Score
- Matching Skills
- Missing Skills

All outputs are structured and machine-readable.

---

## ⚡ Key Features

- Semantic evaluation instead of keyword filtering
- Explainable AI scoring
- Fully automated workflow
- Scalable for bulk resume uploads
- No manual screening required

---

## 🛠️ Technologies Used

- **n8n** – Workflow automation
- **Google Gemini API** – Semantic resume analysis
- **JavaScript** – Data mapping & transformations
- **Google Drive API** – Resume ingestion
- **Google Sheets API** – Result storage
- **PDF Parsing** – Resume & JD extraction

---

## 📈 Scalability

- Supports **multiple resume uploads in parallel**
- Can evaluate **dozens of resumes per execution**
- Easily extendable to large-scale hiring pipelines

---

## 🔧 Possible Improvements

This project is functional but intentionally iterative. Future enhancements include:
- Phone number normalization (numeric validation)
- Score-based notifications (e.g., alert recruiters for 85+ candidates)
- Resume ranking dashboard
- Database integration
- Multi-role JD support

---

## 🎯 Why This Project Matters

This system demonstrates:
- Real-world AI integration
- Automation-first engineering
- LLM output handling and reliability
- Practical ATS problem-solving

It reflects how modern hiring systems should work.

---

## 👩‍💻 Author

**Saakshi Dewangan**  
Software Developer | AI & Automation Enthusiast  

---

⭐ If you found this project interesting, feel free to star the repo!


