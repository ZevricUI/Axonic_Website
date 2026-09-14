# Axonic Hub Website

## Free hosting: GitHub Pages

1. Create a **public** GitHub repository, e.g. `axonic-hub`.
2. Upload everything inside this folder. `index.html` must be in the repository root.
3. On GitHub open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site.
7. Your site will be available at:
   `https://YOUR-GITHUB-USERNAME.github.io/REPOSITORY-NAME/`

## Editing scripts

All scripts are in `scripts.js` inside the `SCRIPTS` array. Each entry contains:
- name
- status
- description
- features
- image
- loadstring

For a new thumbnail, put the image in `assets/` and set the `image` field to its filename.

The Discord button currently points to:
https://discord.gg/axonic

Premium prices currently shown:
- Monthly: $4.99
- Lifetime: $9.99

The site is static, so there is no server/database required.
