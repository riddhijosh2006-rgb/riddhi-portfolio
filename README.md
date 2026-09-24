# Riddhi Joshi — Portfolio

Personal portfolio website for Riddhi Joshi, a final-year B.Tech Computer Science / Data
Science student. Built with plain HTML, CSS, and JavaScript — no frameworks, no backend,
no build step.

## Folder structure

```
portfolio/
├── index.html
├── style.css
├── script.js
├── assets/
│   ├── images/
│   └── resume/
│       └── Riddhi_Joshi_Resume.pdf   ← add your resume here
└── README.md
```

## Before you publish — replace these placeholders

Search each file for the text below and replace it with your real information.

| Placeholder | Where | Replace with |
|---|---|---|
| `GITHUB_LINK_HERE` | `index.html`, each project card | Link to that project's GitHub repo |
| `GITHUB_PROFILE_URL` | `index.html` (hero, GitHub CTA section, footer) | Your GitHub profile URL |
| `YOUR_EMAIL` | `index.html` (Contact), `script.js` (`CONTACT_EMAIL`) | Your email address |
| `YOUR_LINKEDIN_URL` | `index.html` (Contact, footer) | Your LinkedIn profile URL |
| `YOUR_GITHUB_URL` | `index.html` (Contact, footer) | Your GitHub profile URL |
| `COMPANY_NAME`, `START_DATE`, `END_DATE` | `index.html` (Experience) | Your internship details |
| `COLLEGE_NAME`, `START_YEAR`, `END_YEAR` | `index.html` (Education) | Your college and years |
| `STATUS_PLACEHOLDER` | `index.html` (Achievements) | e.g. "Participated", "Applied", "Finalist" |
| `CERTIFICATION_NAME`, `ISSUER`, `DATE` | `index.html` (Certifications) | Your certification details, or delete the card |
| `assets/resume/Riddhi_Joshi_Resume.pdf` | file system | Add your actual resume PDF at this path |

Only put in what's true — leave a placeholder or remove the block rather than inventing
a company, award, or certification.

## Run it locally

No build tools needed.

**Option A — just open it**
Double-click `index.html`, or right-click → Open with → your browser.

**Option B — local server (recommended, avoids some browser file:// quirks)**
```bash
cd portfolio
python3 -m http.server 8000
```
Then visit `http://localhost:8000` in your browser.

## Upload to GitHub

```bash
cd portfolio
git init
git add .
git commit -m "Initial portfolio commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

## Deploy with GitHub Pages

1. Push the project to a GitHub repository (steps above).
2. On GitHub, open the repo → **Settings** → **Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Set **Branch** to `main` and folder to `/ (root)`, then **Save**.
5. Wait a minute, then your site will be live at:
   `https://YOUR_USERNAME.github.io/YOUR_REPO/`

If you want it at the root of `YOUR_USERNAME.github.io` (no repo name in the URL), name
the repository exactly `YOUR_USERNAME.github.io`.

## Notes

- The contact form uses `mailto:` — it opens the visitor's email client pre-filled with
  their message. It does **not** send email on its own. To actually receive submissions
  without opening the visitor's mail client, connect it to a form backend (e.g. Formspree)
  or your own server.
- All content follows what was actually provided — no fabricated companies, GitHub repos,
  awards, or certifications. Replace placeholders honestly as your real details are ready.
