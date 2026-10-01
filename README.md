# StudyFlow – Student Productivity Dashboard

A premium lavender/purple SaaS-style dashboard built with **HTML5, CSS3 and vanilla JavaScript**. No backend, no API keys. All data is stored in `localStorage`.

## Features
- **Dashboard**: gradient banner, live stats, progress bars/rings, today's tasks & schedule, weekly chart, deadlines, focus stats
- **My Tasks**: add/edit/delete, priority, due date/time, search, filter (all/pending/completed/overdue), sort
- **Study Planner**: Mon–Sun timetable, pastel subject colours, completion, today highlight, planned hours
- **Focus Timer**: Pomodoro (focus/short/long), animated ring, pause/resume/reset, session counter, sound, timestamp-based so it survives tab throttling and page refresh
- **Assignments**: statuses, deadline indicators, search/filter/sort, summary
- **Analytics**: Chart.js charts (week/month) built from real activity
- **Quick Notes**: pin, subjects, search, created/edited dates
- **Settings**: name, light/dark, accent colour, timer durations, sound, JSON export/import, reset
- Responsive drawer navigation, toasts, confirm dialogs, reduced-motion support

## Technologies
HTML5 · CSS3 (variables, grid, flexbox) · Vanilla JS · Chart.js (CDN) · Plus Jakarta Sans (Google Fonts)

## Run locally
Open `index.html` in a browser, or serve it: `python3 -m http.server 8000` then visit http://localhost:8000.

## Deploy to GitHub Pages
1. Push these files to a GitHub repo.
2. Go to **Settings → Pages**.
3. Under *Build and deployment*, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
4. Your site will be live at `https://<username>.github.io/<repo>/`.
