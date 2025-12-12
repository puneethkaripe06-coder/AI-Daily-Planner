# AI-Daily-Planner 

PlannerAI Pro – AI Daily Planner
PlannerAI Pro is a modern, AI-powered daily productivity planner built using pure HTML, CSS, and JavaScript. It helps users plan tasks intelligently, focus better using Pomodoro, and track productivity visually — all in a single-page app with a premium UI.
This project was built as part of a hackathon to demonstrate how AI + UX can improve daily productivity.

✨ Key Features
📋 Smart Task Management
* Add tasks with priority (High / Medium / Low) and optional time
* Mark tasks as completed
* Auto-sort tasks by time → priority → creation
* Persistent storage using LocalStorage
  
⏱️ Focus Mode (Pomodoro Timer)
* Pomodoro (25 min), Short Break (5 min), Long Break (15 min)
* Dedicated Focus Mode screen
* Helps users stay distraction-free
* Tracks completed Pomodoro cycles

🧠 AI Assistant (Offline-Friendly)
* Ask AI for:
    * Task prioritization
    * Morning routines
    * Weekly planning
    * Productivity tips
* Works without external APIs using a smart local AI fallback
* Designed to be easily extendable to real LLMs (OpenAI / Gemini)
⚡ Auto-Scheduling Engine
* Automatically assigns time slots to tasks without time
* Prioritizes High → Medium → Low
* Uses 30-minute smart scheduling blocks

📊 Productivity Analytics
* Completion rate (%)
* Average tasks per day
* Daily productivity streak
* Visual stats dashboard

🔔 Motivation Engine
* Periodic motivational toast notifications
* Encourages focus, hydration, and consistency
📄 Export Daily Productivity Report (PDF)
* One-click PDF export
* Includes:
    * Completed tasks
    * Pomodoro cycles
    * AI summary
    * Day mood
    * Productivity streak

🖥️ Tech Stack
* HTML5
* CSS3 (Glassmorphism UI + Animations)
* Vanilla JavaScript
* LocalStorage API
* jsPDF (for PDF export)

🚀 How to Run Locally
1. Clone the repository:    git clone https://github.com/<your-username>/plannerai-pro.git
2. Open the project:    **cd plannerai-pro**
3. Open the file:
    * Double-click index.html OR
    * Right-click → Open with Browser
