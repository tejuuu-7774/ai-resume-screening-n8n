# AI Resume Screening Workflow (n8n)

## Overview
This project is an automated resume screening system built using n8n.  
It compares candidate resumes with a job description using an AI model and sends automated email responses based on the evaluation.

---

## Features

- AI-based resume vs job description matching  
- Candidate scoring and evaluation  
- Automated decision making (selected/rejected)  
- Email notifications using SMTP  
- Fully automated workflow pipeline  
- Simple upload interface using HTML and CSS  

---

## Tech Stack

- n8n (workflow automation)  
- Groq API (LLM for resume analysis)  
- SMTP (email automation)  
- HTML + CSS (upload interface)  

---

## Workflow

1. Input resume and job description  
2. Extract text from uploaded PDF files  
3. Merge and prepare data for processing  
4. Send data to AI model via API  
5. Parse AI response (score, decision, reason)  
6. Apply decision logic (score threshold)  
7. Send email to candidate  

---

## Workflow Screenshot
<img width="1360" height="408" alt="Screenshot 2026-04-09 at 5 44 08 PM" src="https://github.com/user-attachments/assets/f1b9a266-842a-4114-bd4f-f9d8791c0fd1" />

---

## Project Structure
├── resume_screener.json # Exported n8n workflow
├── upload.html # Upload interface
├── upload.css # Styling
├── README.md


---

## How to Use

1. Import `resume_screener.json` into n8n  
2. Add your Groq API key  
3. Configure SMTP credentials  
4. Activate or run the workflow  
5. Open `upload.html` in a browser and upload files  

---

## Use Case

This system helps automate resume screening and reduces manual effort in hiring processes by providing consistent AI-based evaluation of candidates.

---

## Author

Tejaswini Palwai
