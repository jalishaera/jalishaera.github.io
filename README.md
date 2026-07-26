# Jalisha Jashim Era — Portfolio Website

A simple, single-page academic portfolio built with plain HTML/CSS (no build tools required), modeled after a typical PhD-applicant portfolio.

## Files
- `index.html` — the whole site (Home, About, Publications, Teaching, Education, Contact)
- `css/style.css` — styling
- `images/profile-placeholder.svg` — placeholder avatar (replace with a real photo)
- `files/CV-placeholder.pdf` — add your real CV here with this exact filename, or update the link in `index.html`

## What's already real (pulled from your CV and papers)
- Name, email (ira16jalisa@gmail.com), GitHub, and LinkedIn links
- Education (AUST B.Sc. CGPA 3.917, HSC, SSC) and achievements/scholarships
- Research interests and technical skills
- Academic projects
- Both publications, with correct status (ICCIT 2024 = Accepted, SOMADHAN paper = Preprint)
- Teaching Experience: real courses by semester (Fall 2024, Spring 2025, Fall 2025), all labs except Environment and Sustainable Computing (Theory)

## What's still a placeholder — search `index.html` for `[Placeholder ...]`
- **About Me**: the closing sentence inviting you to add your teaching philosophy / PhD motivation.
- **CV file**: `files/CV-placeholder.pdf` is a stub — replace it with your actual CV PDF (keep the same filename, or update the link in `index.html`).
- **Google Scholar**: not listed in your CV, so it's marked "(coming soon)" — update once you have a profile.
- **Phone number**: intentionally left off the public Contact section (common practice to avoid spam); add it if you'd prefer it visible.
- **References**: shown as "available upon request" rather than publishing your referees' personal contact details — add them directly if you'd like them public instead.

## Hosting on GitHub Pages

1. Create a new GitHub repository. For a **user site**, name it exactly `<your-username>.github.io`. For a **project site**, any repo name works.
2. Push these files to the repository root:
   ```
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment", set **Source** to "Deploy from a branch", branch `main`, folder `/ (root)`. Save.
5. Wait a minute, then visit:
   - User site: `https://<your-username>.github.io`
   - Project site: `https://<your-username>.github.io/<repo-name>`

That's it — GitHub Pages will rebuild automatically on every push to `main`.
