# 🧠 AI Resume Screening Automation (Make.com + Gemini)

A **no-code AI Resume Screening system** built using **Make.com**, **Google Gemini AI**, and a lightweight **HTML + JavaScript UI**.

This project automatically analyzes resumes against recruiter-style job descriptions and returns a structured hiring recommendation such as **Reject**, **Review**, or **Interview**.

---

## 🚀 Features

- 📄 Upload resumes (PDF/DOCX)
- 🧑‍💼 Select job role (auto-filled recruiter-style job description)
- 🤖 AI-powered resume analysis using Gemini
- 📊 Structured screening output:
  - Skill match percentage
  - Experience match
  - Fit score
  - Red flags
  - Final recommendation
- 🔄 Fully automated using Make.com
- ⚡ Synchronous UI response using Make.com Webhook Response
- 🧩 No backend required (pure no-code + frontend)

---

## 🏗️ Project Structure

```text
resume-screening-automation/
├── index.html
├── roles-config.js
└── make_com_resume_screening_workflow.blueprint.json