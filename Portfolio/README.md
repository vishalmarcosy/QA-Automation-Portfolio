# Vishal Yadav — QA Automation Portfolio

Personal portfolio site for Vishal Yadav, QA Automation Engineer (Playwright, TypeScript, Selenium, API Testing, CI/CD).

Built with plain HTML, CSS, and JavaScript — no build step required.

## Structure

```
index.html
css/style.css
js/script.js
assets/images/profile.jpg     <- add your photo here
assets/resume/Vishal_Yadav_QA_Automation.pdf   <- add your resume PDF here
```

## Before deploying

1. Add your photo to `assets/images/profile.jpg` (square, 500x500px+ recommended).
2. Add your resume PDF to `assets/resume/Vishal_Yadav_QA_Automation.pdf`.
3. Delete the two placeholder `.txt` files in those folders once done.

## Run locally

Just open `index.html` in a browser, or serve it:

```
npx serve .
```

## Deploy to GitHub Pages

This repo is set up for: https://github.com/vishalmarcosy/QA-Automation-Portfolio

```
git init
git add .
git commit -m "Initial portfolio site"
git branch -M main
git remote add origin https://github.com/vishalmarcosy/QA-Automation-Portfolio.git
git push -u origin main
```

Then in the GitHub repo: **Settings → Pages → Source → Deploy from branch → main / (root)**.

Your site will be live at:
`https://vishalmarcosy.github.io/QA-Automation-Portfolio/`
