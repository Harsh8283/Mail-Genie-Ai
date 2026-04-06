# 🚀 SmartMail AI – Email Response Automation System

## 📧 Overview
SmartMail AI is an AI-powered email automation system that processes incoming emails and generates intelligent, context-aware reply drafts automatically.

Built using **n8n workflows** and **Google Gemini AI**, this system classifies emails and creates appropriate responses, reducing manual effort and improving efficiency.

---

## ✨ Features
- 📥 Automatically detects incoming emails using Gmail Trigger
- 🧠 AI-based email classification (e.g., Support, General Queries)
- ✉️ Generates smart responses using Google Gemini (LLM)
- 📝 Creates draft replies directly in Gmail
- ⏱️ Implements rate limiting for stable processing
- 🔀 Workflow branching for different email types

---

## 🛠️ Tech Stack
- **n8n** – Workflow automation
- **Google Gemini API** – AI response generation
- **Gmail API** – Email integration
- **LLM-based Text Classification**

---

## 🔄 Workflow Architecture
📥 Gmail Trigger
->
⏱️ Rate Limiter
->
🧠 Text Classification (AI)
->
🔀 Conditional Routing (IF Node)
->
✉️ AI Response Generation (Gemini)
->
📝 Gmail Draft Creation

💡 Use Cases
 1.Automated customer support replies
 2.Email triaging and sorting
 3.Personal productivity assistant
 4.Business email automation

 ## 🔗 Workflow Access

Due to access restrictions in n8n cloud, the workflow cannot be shared via a public link.

However, you can:
- Download the workflow JSON file
- Import it directly into your n8n instance

👉 👉 [Download workflow.json](https://raw.githubusercontent.com/AryanKumar9798/Mail-Genie-AI/main/My%20workflow.json)


 Screenshot-
 <img width="1153" height="601" alt="image" src="https://github.com/user-attachments/assets/a699b918-fde2-4e0d-81cc-d51f1859b506" />


 👨‍💻 Author
 Harsh anand
