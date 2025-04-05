✅ Day 1 Summary – Project Setup (HISApp)
📌 Goal:
Kickstart development of a full-stack Hospital Information System (HIS) using:

✅ React (Frontend)

✅ ASP.NET Core Web API (Backend)

✅ Git + GitHub for version control

🛠️ What You Set Up
✅ 1. Project Folder Structure
bash
Copy
Edit
HISApp/
├── hisapp-web       # React frontend (Vite)
├── HISApp.API       # ASP.NET Core Web API
✅ 2. React Frontend Setup
Used Vite to scaffold a modern React app

Installed Node.js and ran:

bash
Copy
Edit
npm create vite@latest
npm install
npm run dev
React is now running at: http://localhost:5173 ✅

✅ 3. ASP.NET Core API Setup
Created a new .NET 8 Web API project:

bash
Copy
Edit
dotnet new webapi -n HISApp.API
Launched the API:

bash
Copy
Edit
cd HISApp.API
dotnet run
API now listening on: http://localhost:5062 ✅

✅ 4. Git & GitHub
Initialized Git:

bash
Copy
Edit
git init
Set Git username/email:

bash
Copy
Edit
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
Created and committed your first snapshot:

bash
Copy
Edit
git add .
git commit -m "Day 1: Initial setup - React + .NET Core API"
Created remote repo on GitHub and connected:

bash
Copy
Edit
git remote add origin https://github.com/yourusername/HISApp.git
git branch -M main
git push -u origin main
✅ GitHub now hosts your full project!

📘 Helpful Links
🔗 Git Cheat Sheet (Notion)

📄 Sample GitHub README

🔗 React Docs

🔗 .NET Core Docs

🧠 What You Learned
How to set up a full-stack app with React and ASP.NET Core

How to run both frontend and backend locally

How Git tracks changes and GitHub stores your code

How to push commits to GitHub for safe versioning