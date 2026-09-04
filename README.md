# EDU Seat Plan Generator
### East Delta University — Examination Division

A fully static, browser-based seat plan generator. No server, no backend, no installation — just open `index.html`.

---

## How to use

1. Fill in **Exam Details** (name, date, time)
2. Configure **Rooms** — set rows × columns for each room, mark building (main/novus)
3. Add **Courses** with student counts
4. Click **⚡ Generate Seat Plan**
5. Click **🖨 Print / Export PDF** to save

---

## How to host on GitHub Pages (free, permanent link)

1. Go to **github.com** → click **New repository**
2. Name it: `seat-plan` (or anything you like)
3. Set visibility: **Public**
4. Click **Create repository**
5. Upload `index.html` (drag and drop into the repo page)
6. Go to **Settings → Pages**
7. Under *Source*, select **Deploy from a branch → main → / (root)**
8. Click **Save**
9. After ~60 seconds, your app is live at:
   `https://YOUR-USERNAME.github.io/seat-plan/`

Share that link with anyone in your department — it works on any device, any browser.

---

## Seating Rule
The generator follows the anti-adjacency rule from EDU's exam policy:
> No two students of the same course may sit in adjacent seats (horizontally, vertically, or diagonally).

This is achieved by dividing each room into 4 sub-grids (SG1–SG4), each assigned to exactly one course.

---

## Customising rooms

Each semester, just update the room list and student counts — the layout recalculates instantly. To add a new room type, set its rows and columns and mark whether it is in the main or Novus building. The engine handles the rest.

---

*Built for East Delta University · Chattogram, Bangladesh*
