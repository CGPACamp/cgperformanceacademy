# Coastal Georgia Performance Academy Coming Soon Site

Static one-page website for GitHub Pages.

## Upload to GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, and the `assets` folder.
3. Go to Settings > Pages.
4. Choose Deploy from branch.
5. Select `main` and `/root`, then Save.
6. Add your custom domain: `cgperformanceacademy.com`.

## GoDaddy DNS for GitHub Pages
Add these A records for `@`:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Add this CNAME record:
- Name: www
- Value: YOUR-GITHUB-USERNAME.github.io

After GitHub verifies, turn on Enforce HTTPS.
