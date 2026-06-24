# nulldonut / portfolio

Minimal developer portfolio — projects, skills, and links.

## Deploy to GitHub Pages

1. **Create the repo**  
   On GitHub, create a repo named `nulldonut.github.io` (must match your username exactly).

2. **Push the site**  
   ```bash
   git init
   git add .
   git commit -m "initial"
   git remote add origin https://github.com/nulldonut/nulldonut.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable Pages**  
   Go to repo → Settings → Pages → deploy from `main` branch, root folder.  
   Your site will be live at `https://nulldonut.github.io` within a couple minutes.

## Custom domain (optional)

Add a `CNAME` file with your domain, or set it in the Pages settings.
