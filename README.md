# TalkNinja School Edition — Prototype

Frontend-only prototype. No backend, no auth — all data is hardcoded.

## Running the apps

### Coach Dashboard
```bash
cd dashboard && npm install && npm start
```
Opens at **http://localhost:5173**

### Student Preview
```bash
cd student-preview && npm install && npm start
```
Opens at **http://localhost:3001**

---

## What's inside

### `/dashboard` — Coach Dashboard (React + Tailwind + Recharts)
- **Roster** — 8 students with status, last active, session count, avg score, assignment completion
- **Assignments** — Create form + active assignment with per-student completion chips
- **Reports** — Student grid → click → skill breakdown bars, radar chart, score trend lines, session history

### `/student-preview` — Student App (React + phone frame)
- **Home Screen** — School branding (Westlake Debate Academy), assigned challenge card with countdown, daily challenge, speech type explorer
- **Results Screen** — Overall tab (score, star ratings, analysis, tips) + Analysis tab (pacing chart, filler word transcript)

### Mock data
- School: **Westlake Debate Academy** · Coach: **Ms. Patel**
- 8 students with 5 sessions of skill data each
- Active assignment: *"Should AI be regulated?"* — Congressional, 2 min, due in 3 days
