# Deploy to GitHub Pages

## Recommended repository
Create a public repository named:

`YOUR-GITHUB-USERNAME.github.io`

This gives a clean personal-site URL:

`https://YOUR-GITHUB-USERNAME.github.io/`

## Upload
Upload all files and folders from this project to the repository root, then commit to `main`.

## Enable Pages
GitHub → repository → Settings → Pages → Build and deployment → Source → **GitHub Actions**.

The included `.github/workflows/deploy.yml` builds the Vite app and deploys `dist/` automatically whenever you push to `main`.

## Important
Before making the repository public, review `public/assets/Shafeeq-Ayman-N-Resume.pdf` and the public portfolio content to ensure no confidential client information is included.
