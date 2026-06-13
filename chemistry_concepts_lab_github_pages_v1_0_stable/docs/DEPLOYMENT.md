# Deployment Guide

## Option 1: Upload through GitHub UI

1. Create a new GitHub repository, for example `chemistry-concepts-lab`.
2. Upload all files from this folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.
6. Open the GitHub Pages URL after deployment completes.

## Option 2: Local Git commands

```bash
git init
git add .
git commit -m "Deploy Chemistry Concepts Lab stable"
git branch -M main
git remote add origin https://github.com/<your-user>/<your-repo>.git
git push -u origin main
```

Then enable Pages from **Settings → Pages** using the root folder.

## File to open locally

Open `index.html` in any modern browser.
