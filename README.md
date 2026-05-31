# Madhu Sudhan Painoori — Portfolio

A single-page portfolio site for hosting on **GitHub Pages**. No build step, no dependencies — just static files.

Live URL (once deployed): **https://madhu-sudhan-painoori.github.io**

---

## What's in this folder

```
portfolio/
├── index.html          <- the portfolio page (open this to preview locally)
├── README.md           <- this file
└── assets/
    ├── resume.pdf          <- executive resume (linked from the page)
    ├── playbook.pdf        <- AI-QA Transformation Playbook (12 pages)
    ├── playbook.docx       <- editable version of the playbook
    ├── infographic.png     <- architecture diagram, shown inline + downloadable
    └── infographic.pdf     <- architecture diagram, print quality
```

To preview locally, just double-click `index.html` and it opens in any browser.

---

## Deploy to GitHub Pages (about 5 minutes)

### Option A - the username site (recommended, cleanest URL)

This produces the URL **https://madhu-sudhan-painoori.github.io** (no repo name in the path).

1. Create a GitHub account if you don't have one, at https://github.com. Your username should ideally be `madhu-sudhan-painoori` so the URL matches. If that username is taken, pick another and your URL becomes `https://<your-username>.github.io`.

2. Create a new repository named exactly:
   ```
   madhu-sudhan-painoori.github.io
   ```
   Replace `madhu-sudhan-painoori` with your actual GitHub username. The repo name MUST be `<username>.github.io` for this to work.
   - Set it to Public.
   - Do NOT add a README (this folder already has one).

3. Upload the files. On the new repo's page, click "uploading an existing file", then drag in:
   - `index.html`
   - the entire `assets` folder (drag the folder itself - GitHub preserves the structure)
   - `README.md`

   Click Commit changes.

4. Enable Pages. Go to Settings -> Pages. Under "Build and deployment", set Source = Deploy from a branch, Branch = main, Folder = / (root). Click Save.

5. Wait about 1 minute, then visit https://madhu-sudhan-painoori.github.io. Done.

### Option B - a project site (if you'd rather not use the username repo)

This produces a URL like `https://<username>.github.io/portfolio`.

1. Create any public repository (e.g. named `portfolio`).
2. Upload `index.html`, the `assets` folder, and `README.md`.
3. Settings -> Pages -> Source = Deploy from a branch -> Branch = main -> / (root) -> Save.
4. Your site will be live at `https://<username>.github.io/portfolio` after about 1 minute.

---

## Updating the site later

- Swap in a new resume or playbook: replace the file in `assets/` (keep the same filename) and commit. The page links update automatically.
- Edit the text: open `index.html`, edit, commit. Changes go live within a minute.
- Change the LinkedIn / email / phone: they live near the bottom of `index.html` in the contact section.

---

## Using a custom domain (optional, later)

If you ever buy a domain like `madhupainoori.com`:
1. In your domain registrar, add a CNAME record pointing to `madhu-sudhan-painoori.github.io`.
2. In the repo, Settings -> Pages -> Custom domain, enter your domain and Save.
3. Tick Enforce HTTPS once it's available.

---

## After it's live - where to put the URL

- LinkedIn: Contact info -> Website, and in your headline/about
- Resume: the contact line
- Email signature
- Every recruiter and reverse-pitch outreach

That single URL becomes the front door to your resume, playbook, and architecture - everything in one place.
