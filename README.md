# Portfolio Website

This is a simple static portfolio site built with plain HTML and CSS.

How to use
1. Customize `index.html`:
   - Replace "Your Name", bio, projects, links, and email.
   - Add images or screenshots (place them in a `images/` folder and reference them).
2. Edit `styles.css` to change colors, fonts, spacing.

Run locally
- Option A: Open `index.html` in your browser.
- Option B: Serve with a simple HTTP server (recommended for some browser features):
  - Python 3: `python -m http.server 8000`
  - Navigate to `http://localhost:8000`

Publish to GitHub and enable GitHub Pages
1. Create a repository on GitHub (e.g. `portfolio`) or use the GitHub CLI:
   - `gh repo create YOUR_USERNAME/portfolio --public --source=. --remote=origin --push`
2. Or manual git commands:
   - `git init`
   - `git add .`
   - `git commit -m "Initial commit"`
   - `git branch -M main`
   - Create a repo on GitHub via the website, then:
     - `git remote add origin https://github.com/YOUR_USERNAME/portfolio.git`
     - `git push -u origin main`
3. Enable GitHub Pages:
   - In the repository on GitHub: Settings → Pages → Source → choose "Deploy from a branch" → `main` branch, folder `/ (root)` → Save.
   - Your site will be available at `https://YOUR_USERNAME.github.io/portfolio/` (or `https://YOUR_USERNAME.github.io/` if you named the repo `YOUR_USERNAME.github.io`).

Optional: Use a custom domain
- Add a `CNAME` file containing your domain name.
- Configure DNS to point to GitHub Pages (see GitHub Pages docs for instructions).

Accessibility & improvements
- Add alt text to images.
- Ensure color contrast is sufficient.
- Make the site responsive (the sample is responsive).
- Consider adding a resume PDF, links to LinkedIn, Twitter, and deployment previews.

License
- Use and adapt this template however you like.