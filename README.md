# AI Resume Screening Workflow (n8n)

## Overview
This project is an automated resume screening system built using n8n.  
It compares candidate resumes with a job description using AI and sends automated email responses.

---

## Features
- AI-based resume vs job description matching
- Candidate scoring and evaluation
- Automated decision making (selected/rejected)
- Email notifications using SMTP
- Fully automated workflow pipeline

---

## Tech Stack
- n8n (workflow automation)
- Groq API (LLM for resume analysis)
- SMTP (email automation)

---

## Workflow
1. Input resume and job description  
2. Send data to AI model via API  
3. Parse AI response (match, score, reason)  
4. Apply decision logic  
5. Send email to candidate  

---

## Workflow Screenshot
<img width="1303" height="343" alt="Screenshot 2026-04-08 at 10 09 04 AM" src="https://github.com/user-attachments/assets/380839de-ffe3-44f2-87a9-e40f52d2066a" />


---

## Files
- `workflow.json` → Exported n8n workflow

---

## How to Use
1. Import `workflow.json` into n8n  
2. Add your Groq API key  
3. Configure SMTP credentials  
4. Run the workflow  

---

## Use Case
Helps automate resume screening and reduces manual effort in hiring processes.

---

## 👩‍💻 Author
Teju
