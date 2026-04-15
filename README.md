# Harika Gundla Portfolio

This is a simple static portfolio website built with HTML and CSS.

## Included Files
- `index.html` — main portfolio page
- `style.css` — styling for the portfolio
- `image.jpeg` — your profile image used in the portfolio

## Deploy Permanently with GitHub Pages

### 1. Install Git
If Git is not installed yet, download and install it from:
- https://git-scm.com/downloads

### 2. Create a GitHub repository
1. Sign in to GitHub.
2. Create a new repository named `my_portfolio`.
3. Do not add a README or license if you want to push your local files directly.

### 3. Initialize and push your project
Open PowerShell in the project folder and run:
```powershell
cd "C:\Users\GUNDLA HARIKA\Documents\my_portfolio"
git init
git add .
git commit -m "Initial portfolio deployment"
git branch -M main
git remote add origin https://github.com/harikagundla/my_portfolio.git
git push -u origin main
```

### 4. Enable GitHub Pages
1. Open your repository on GitHub.
2. Go to `Settings` > `Pages`.
3. Under `Source`, choose `Deploy from a branch`.
4. Select `main` branch and `/ (root)` folder.
5. Save.

Your site will publish at:
- `https://harikagundla.github.io/my_portfolio/`

## Alternative: Netlify or Vercel
If you prefer a drag-and-drop or connected deployment:

### Netlify
1. Create a Netlify account.
2. Choose `New site from Git` and connect GitHub.
3. Select your repository.
4. Use default build settings (no build command, publish directory = `.`).

### Vercel
1. Create a Vercel account.
2. Import the GitHub repository.
3. Deploy the site.

## Local Preview
You can preview the site locally by opening `index.html` in your browser.

---

If you want, I can also help you create the GitHub repo and configure the deployment commands step by step.