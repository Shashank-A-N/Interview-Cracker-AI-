# Interview Cracker AI 🚀  

**Interview Cracker AI** is your personal, AI-powered coach for acing job interviews!  
This lightweight, single-file web application helps you prepare for every stage of the interview process—from aptitude tests to final HR rounds.  
Powered by the **Gemini API**, it provides personalized prep plans, realistic practice sessions, and intelligent feedback to get you job-ready.  

---

## ✨ Features  

### 🤖 AI Prep Plan Generator  
- **Personalized Strategy**: Paste any job description—or just a job title—and get a tailored step-by-step preparation plan.  
- **Key Insights**: Identifies required skills, potential questions across Aptitude, Coding, Technical, and Behavioral rounds.  
- **Curated Resources**: Custom 2–4 week study roadmap + recommended YouTube videos.  

### 🧠 General Interview Round Guides  
- **Detailed Guides**: Aptitude, Coding, Group Discussion, Technical Rounds 1 & 2, and HR Round.  
- **Targeted Topics**: Breakdowns of key concepts for each round.  

### 💻 Interactive Practice Zone  
- **Aptitude & Technical MCQs**: Practice Quantitative Aptitude, Logical Reasoning, DBMS, Operating Systems, etc.  
- **Realistic Coding Environment**: IDE-like editor with test case runner.  
- **Real Code Execution**: JavaScript runs directly in-browser, other languages simulated.  
- **Smooth Navigation**: Previous/Next question support.  

### 💡 AI-Powered Assistance  
- **AI Project Interrogator**: Enter your project, get deep-dive technical questions.  
- **AI Mock Interview**: Conversational HR round simulation with intelligent feedback.  
- **AI Code Explanation**: Line-by-line explanations with logic + time/space complexity.  
- **Personalized Aptitude Feedback**: Tips based on your wrong answers.  

### 🎬 Resource Video Library  
- Hand-picked YouTube videos for Aptitude, DSA, System Design, and HR prep.  

---

## 🚀 Getting Started  

This application is **100% frontend**—no servers or build tools required. Just one HTML file!  

### Prerequisites  
- A modern web browser (Chrome, Firefox, Edge).  
- A **Gemini API key**.  

### Installation & Running  
1. **Save the Code**: Copy the code and save it as `index.html`.  
2. **Add Your API Key**:  
   - Open `index.html` in a text editor.  
   - Find this line:  
     ```js
     const apiKey = "YOUR_API_KEY_HERE";
     ```  
   - Replace `"YOUR_API_KEY_HERE"` with your **Gemini API key**.  
3. **Run the App**: Double-click `index.html` to open it in your browser. 🎉  

---

## 🛠️ How It Works  

- **Frontend**: Built with **HTML + Tailwind CSS + JavaScript**.  
- **AI Integration**: Uses Gemini’s `gemini-2.5-flash-preview-05-20` model for prep plans, Q&A, and feedback.  
- **State Management**: A central JavaScript object stores state; `render()` updates the UI.  
- **Code Execution**:  
  - JavaScript code: Executed in-browser using `new Function()`.  
  - Other languages: Simulated execution.  

---

## 📌 Tech Stack  

- **HTML5**  
- **Tailwind CSS (via CDN)**  
- **Vanilla JavaScript**  
- **Google Gemini API**  

---

## 🎯 Why Use Interview Cracker AI?  

- Lightweight ⚡ (single HTML file, no backend required)  
- Portable 🛠 (runs locally in any browser)  
- Customizable 🎨 (easy to edit/extend features)  
- AI-powered 🚀 (personalized prep with real feedback)  

---

## 📜 License  
This project is licensed under the **MIT License** – feel free to use, modify, and share.  

---
