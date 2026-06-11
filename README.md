# OCEO 2.0 — UX Prototype

An AI-driven relationship platform for the **Office of the CEO** at a Big-5 Canadian bank. This repository holds a clickable, single-file HTML prototype used to walk Vice Chairs through the proposed experience across the three core scenarios: **pre-meeting**, **during-meeting**, and **post-meeting**.

> All names and figures shown are **illustrative sample data**. The structure, fields, and data sources are drawn from the OCEO 2.0 requirements.

---

## Quick start

Every screen is a **self-contained HTML file** — no build step, no dependencies, no install. You can open any file directly in a browser, or serve the folder.

### Open in GitHub Codespaces
1. On the repo page: **Code ▸ Codespaces ▸ Create codespace on main**.
2. In the Codespace terminal, serve the folder:
   ```bash
   python3 -m http.server 8000
   ```
   (or, if you prefer Node: `npx serve -l 8000`)
3. Codespaces will prompt to **open the forwarded port (8000)** in your browser. Click it, and you'll land on `index.html`.

### Run locally
```bash
# from the repo root
python3 -m http.server 8000
# then visit http://localhost:8000
```
Or simply double-click `index.html` to open it in your browser.

---

## Where to start

Open **`index.html`** — it's the launcher. It links to every screen, and the in-app sidebar navigates between them.

---

## Screens

| File | Screen | Phase |
|---|---|---|
| `index.html` | Launcher / screen directory | — |
| `oceo-portfolio-landing.html` | **Portfolio Landing** (home — book, attention queue, search) | Now |
| `oceo-c360-prototype.html` | **Client 360** (the client one-pager: overview, holdings, connections, notes & tasks, interactions, cases) | Now |
| `oceo-ai-assistant.html` | **CAI** — grounded, cited AI assistant (full-page) | Now |
| `oceo-tasks.html` | **Task List / Status** | Now |
| `oceo-global-search.html` | **Global Search** (fuzzy, parent/portfolio aware) | Now |
| `oceo-rm-touchpoints.html` | **RM email touchpoints** + no-login response form | Now |
| `oceo-exec-dashboard.html` | **Executive Dashboard** (all-clients, drill-in) | Next |
| `oceo-vc-tablet.html` | **VC tablet** one-pager (portrait) | Next |

`CAI` is also available as a slide-in panel on the Now-phase app screens (the "Ask CAI" button).

---

## Design system (at a glance)

- **Color:** charcoal neutral base with CIBC brand red `#C41F3E` as the accent (deeper `#A81733` for hover/active).
- **Type:** Spectral (display/serif) + Inter Tight (UI), loaded from Google Fonts.
- **Icons:** Lucide, inlined as SVG.
- **Roles:** the prototype is locked to the **Vice Chair** experience for this review.

---

## Deployment

A `vercel.json` is included (`cleanUrls` on). To deploy as a static site:

1. Import the repo at [vercel.com/new](https://vercel.com/new).
2. Framework preset: **Other** (no build command, output = repo root).
3. Deploy — `index.html` is served at the root.

---

## Reference

- `OCEO-2.0-VC-Walkthrough-Speaking-Notes.md` — presenter notes for the Vice Chair design review.
