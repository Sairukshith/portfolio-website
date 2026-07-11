# Day 20 Deployment Guide

Use this guide to complete the final Day 20 task: publish the portfolio, share the GitHub repository link, and submit the live website link.

## 1. Create A GitHub Repository

1. Sign in to GitHub.
2. Click `New repository`.
3. Repository name: `portfolio-website`.
4. Keep it `Public`.
5. Click `Create repository`.

## 2. Add The Project Files

Upload these files and folders:

```text
index.html
styles.css
script.js
README.md
DEPLOYMENT.md
assets/
```

The homepage must stay named `index.html`.

## 3. Git Commands

Run these commands from the project folder if you are using Git locally:

```powershell
git init
git add .
git commit -m "Add final portfolio website"
git branch -M main
git remote add origin https://github.com/your-username/portfolio-website.git
git push -u origin main
```

Replace `your-username` with your GitHub username.

## 4. Deploy With GitHub Pages

1. Open your repository on GitHub.
2. Go to `Settings`.
3. Open `Pages`.
4. Under `Build and deployment`, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
5. Click `Save`.

Your live site link will look like:

```text
https://your-username.github.io/portfolio-website/
```

## 5. Optional Netlify Deployment

1. Go to Netlify.
2. Choose `Add new site`.
3. Use manual deploy or connect your GitHub repository.
4. Upload this project folder or select the GitHub repository.
5. Netlify will generate a public live link.

## 6. Submission Format

```text
GitHub Repository: https://github.com/your-username/portfolio-website
Live Website: https://your-username.github.io/portfolio-website/
```

## Short Project Write-Up

This portfolio website was built with HTML5, CSS3, and JavaScript. It includes a responsive layout, sticky navigation, project case study, resume link, contact form, accessible focus states, and a deployment-ready static file structure.

I learned how to organize a website project, write semantic HTML, style responsive sections with CSS Grid and Flexbox, test mobile navigation, and prepare a website for publishing through GitHub Pages or Netlify.

The main challenge was making the website look professional on both desktop and mobile screens. I solved this by using responsive layout rules, flexible spacing, and clear content sections.
