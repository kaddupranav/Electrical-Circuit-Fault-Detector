# Electrical-Circuit-Fault-Detector
working link:https://chatbot.getmindpal.com/24-7-technical-triage-safety-advisor-e3p
# 24/7 Technical Triage & Safety Advisor ⚠️

A full-stack, open-source AI assistant designed to act as a first-line digital responder for field engineers, technicians, and site operators. This application evaluates inbound technical system errors, assesses hazard levels, and provides immediate safety procedures and troubleshooting workflows.

Built entirely using **JavaScript**, this repository features a secure Node.js backend integration powered by Google's Gemini API and an ultra-responsive, zero-dependency browser interface.

---

## 🚀 Key Features

* **Real-Time Risk Triage:** Instantly processes and categorizes inbound technical anomalies and machinery issues.
* **Safety-First Guardrails:** Configured with strict system instructions to prioritize human safety, flashing immediate warnings for high-risk hazards (electrical, pressure, chemical).
* **Context Retention:** Keeps track of conversational history dynamically, ensuring smooth multi-step troubleshooting.
* **Secure Architecture:** Keeps your API keys hidden on the server side, preventing client-side data leaks.
* **Lightweight & Fast:** Uses vanilla frontend code and Express.js, avoiding heavy framework overhead.

---

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (Responsive Design), Vanilla JavaScript (Fetch API)
* **Backend:** Node.js, Express.js, CORS
* **AI Engine:** Official `@google/genai` SDK (`gemini-2.5-flash` model)

---

## 📂 Project Structure

```text
safety-chatbot/
├── index.html          # Frontend user interface
├── server.js          # Node.js Express server
├── package.json       # Dependencies and project metadata
└── .gitignore         # Prevents uploading node_modules to GitHub
