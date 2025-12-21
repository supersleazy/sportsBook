# SportsBook – Frontend UI Concept

SportsBook is a **frontend-only prototype** for a campus sports management platform.  
It visualizes how a unified system could manage sports facilities, players, matches, and bookings within a university or campus environment.

This repository contains **only the frontend layer** (UI/UX + interaction logic).  
Backend services, authentication, and real-time data are intentionally mocked or simulated.

---

## 🚀 Project Vision

Campus sports infrastructure is often fragmented:
- Separate systems for booking
- Manual scorekeeping
- No visibility into occupancy
- No player discovery or matchmaking

**SportsBook** explores how these can be unified into a single platform that supports:
- Students
- Teams
- Facility administrators

---

## 🧩 Features Implemented (UI)

- **Authentication UI**
  - Login, signup, forgot password flows (modal-based)

- **Facility Occupancy Dashboard**
  - Sport-wise availability
  - Equipment status
  - Visual court layouts
  - Timetables and usage analytics

- **Player Search & Matchmaking**
  - Player discovery with filters
  - Team formation workflows
  - Invite & assistance flows

- **Booking System**
  - Venue selection
  - Time-slot booking
  - Availability cards
  - Countdown timer to booking start

- **Live Scoring**
  - Live vs completed matches
  - Scorecards with status badges

- **Utility Flows**
  - QR-based player scan (UI simulation)
  - Coin toss animation for match start
  - Community & feedback sections

---

## 🛠 Tech Stack

- **HTML5**
- **CSS3**
  - Modular, page-specific stylesheets
  - Global theming via CSS variables
- **Vanilla JavaScript**
  - UI state handling
  - Timers & animations
- **Chart.js**
  - Occupancy and usage visualizations

No frameworks were used to focus on:
- Layout fundamentals
- Interaction design
- Platform-level UI thinking

---

## 📁 Project Structure

- `/public` – All HTML pages
- `/css` – Global + page-specific styles
- `/js` – Interaction logic (auth, timers)
- `/assets` – Logos, images, icons

---

## ⚠️ Notes

- This is a **frontend prototype**, not a production system
- No real authentication or backend APIs
- All data is mocked or hardcoded for demonstration

---

## 🔮 Future Scope

- React / Next.js migration
- Backend integration (auth, bookings, live scoring)
- WebSocket-based real-time updates
- Role-based access (students, admins, coaches)

---

## 👤 Author

Built as a UI/UX + frontend systems concept project.

