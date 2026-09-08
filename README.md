 Smart-AI-To-Do-List-application
 Smart AI To-Do — Local Heuristic Task Prioritizer    Here’s the complete working version of your Smart AI To-Do app — combining your HTML, CSS, and JavaScript cleanly.  Built entirely with HTML, CSS, and JavaScript  no frameworks or backend required. 

A modern, offline-first To-Do web app that uses a  local "AI" heuristic algorithm  to prioritize tasks by urgency, importance, and deadlines.  

Built entirely with HTML, CSS, and JavaScript  — no frameworks or backend required.

 Features

- 🧠 Smart Prioritization:
  Ranks tasks using a heuristic "AI" formula that considers:
  - Priority (High / Medium / Low)
  - Deadlines & remaining time
  - Estimated time cost
  - Tags (e.g., `urgent`, `meeting`, `design`)
  - Task age

- 📦 Offline & Local Storage:
  All tasks are stored locally in your browser — no network required.

- 🗓️ Auto Scheduler (Mock):
  Suggests an optimal daily schedule between 9:00 AM and 9:00 PM.

- 🔒 Privacy-First: 
  No user accounts, no data tracking — everything happens in your browser.

- 💡 Expandable:
  Easily connect a real AI model (like OpenAI GPT) by modifying the `computeScores()` function.


🚀 Live Demo

👉 View on GitHub Pages (https://github.com/azuark777-dna/Smart-AI-To-Do-List-application)



🧩 Tech Stack

Layer :Technology 
Frontend:  HTML5, CSS3 (custom styles), Vanilla JavaScript 

Storage :Browser Local Storage 
Hosting :GitHub Pages 



 🛠️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/azuark777-dna/Smart-AI-To-Do-List-application.git




🧠 Scoring Logic Overview

Each task is assigned a score based on:

score = (priorityWeight × importance) + deadlineBoost − timeCostPenalty + tagBonus + ageBoost

Priority Weight: High = 3, Medium = 2, Low = 1

Deadline Boost: Increases when tasks are closer to due time

Estimate Penalty: Longer tasks slightly deprioritized

Tag Bonus: Tags like urgent or meeting improve ranking

Age Boost: Older incomplete tasks gain small boost.




💬 Future Enhancements

🤝 Integrate with real AI (OpenAI API) for task context reasoning

📅 Google Calendar export for scheduled tasks

📊 Task analytics and completion tracking

📱 PWA (Progressive Web App) support for mobile installation
