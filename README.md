# FocusFlow — Task Management App

> A sleek productivity tracker with priority management, filtering, and real-time progress tracking.

## 🚀 Live Demo
Open `index.html` in any browser — no installation required.

## 🛠 Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | HTML5, CSS3 (custom properties, animations), Vanilla JS |
| Data Persistence | localStorage (browser-based database) |
| Fonts | Google Fonts (Syne + DM Mono) |
| Architecture | Single-page application (SPA) |

## ✨ Features
- **Add tasks** with title, category, priority, and due date
- **Priority system** — High / Medium / Low with color-coded badges
- **Filter tasks** by status, priority, or category
- **Progress bar** showing overall completion percentage
- **Overdue detection** — automatically flags past-due tasks
- **Live clock** displaying current date and time
- **Real-time stats** — total, completed, in-progress, high-priority counts
- **Persistent storage** — tasks saved across browser sessions

## 📁 Project Structure
```
focusflow/
├── index.html       # Main app (fully self-contained)
└── README.md        # This file
```

## 🏃 How to Run
```bash
# Option 1 — Just open it
open index.html

# Option 2 — Run a local server
npx serve .
# or
python3 -m http.server 8000
```

## 📌 Problem Solved
Freshman students juggle assignments, projects, and personal tasks with no centralized system. FocusFlow provides a simple, fast, and visually clear task manager that persists data locally — no backend or account required.

## 💡 What I Learned
- DOM manipulation and event-driven programming in JavaScript
- CSS animations and custom properties for design systems
- LocalStorage API for client-side data persistence
- Responsive layout design with CSS Grid

## 🔮 Future Improvements
- [ ] Node.js + Express backend with REST API
- [ ] PostgreSQL database for multi-user support
- [ ] User authentication (JWT)
- [ ] React rewrite for component architecture
- [ ] Drag-and-drop task reordering
- [ ] Email reminders for due dates

---
Built by [Your Name] | CS Freshman Portfolio Project
