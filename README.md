# Keshav Arora — Portfolio

Static site (plain HTML/CSS/JS, no build step).

## Deploy on Vercel
1. Push this folder to a new GitHub repo (index.html must be at the repo root).
2. On vercel.com: **Add New → Project → Import** the repo.
3. Framework preset: **Other**. Leave build command and output directory empty. Click **Deploy**.

(Or with the CLI: `npm i -g vercel` then run `vercel` inside this folder.)

## Add your links
Open `index.html`, search for `const LINKS` near the bottom, and paste your URLs
(LinkedIn, GitHub, project repos). Any link left empty is hidden automatically.

## Files
- `assets/headshot.jpg`, `assets/formal.jpg`, `assets/formal-2.jpg` — your photos
- `assets/Keshav_Arora_Resume.pdf` — the "Download resume" button (replace to update)
