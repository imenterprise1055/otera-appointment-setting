Appointment Scheduler — React Prototype
======================================

What this is
-------------
A single-file React prototype using FullCalendar. It stores appointments in localStorage,
allows choosing a planner, shows an agenda (FullCalendar) and a leaderboard per day.

How to run (recommended: Vite)
------------------------------
1. Install Node.js (LTS) if you don't have it: https://nodejs.org/
2. Create the app (using Vite):
   npm create vite@latest appointment-scheduler -- --template react
   cd appointment-scheduler
3. Replace src/App.jsx with the provided App.jsx file in this package.
4. Replace src/main.jsx and index.css if needed (provided).
5. Install dependencies:
   npm install @fullcalendar/react @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/interaction
6. Start:
   npm install
   npm run dev

Files included:
- package.json (minimal)
- index.html
- src/main.jsx
- src/App.jsx
- src/index.css

Note: This prototype uses localStorage for persistence. If you want multi-user sync,
use Firebase or a backend (I can help).
